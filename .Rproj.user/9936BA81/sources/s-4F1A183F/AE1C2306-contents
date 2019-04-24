library(ggplot2)
library(dplyr, warn.conflicts = F)

theme_set(theme_bw())

ggplot(mtcars, aes(x = mpg, y = disp)) + 
  geom_point() + 
  ggsave("pointchart.png", dpi = 300)


ggplot(infert, aes(education)) + 
  geom_bar() + 
  ggsave("barchart.png", dpi = 300)
  