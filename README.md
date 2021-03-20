# Ramen-ratings
# Clean data
setwd("/Users/sunemilyjiayin/Creative Cloud Files")
ramen <- read.csv("ramen-ratings.csv")
head(ramen)
str(ramen)
ramen <- ramen[c(-1,-7)]
ramen$Stars <- as.numeric(ramen$Stars)
str(ramen)
# modeling country by rates
ramenlm3<-lm(Stars~Country,data=ramen)
summary(ramenlm3)
confint(ramenlm3)
summary(aov(ramenlm3))
# modeling style by rates
ramenlm2<-lm(Stars~Style,data=ramen)
summary(ramenlm2)
confint(ramenlm2)
summary(aov(ramenlm2))
