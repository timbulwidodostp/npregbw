# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Kernel Regression Bandwidth Selection with Mixed Data Types Use npregbw (np) With (In) R Software
install.packages("np")
library("np")
npregbw = read.csv("https://raw.githubusercontent.com/timbulwidodostp/npregbw/main/npregbw/npregbw.csv",sep = ";")
# Estimation Kernel Regression Bandwidth Selection with Mixed Data Types Use npregbw (np) With (In) R Software
gdp <- npregbw$gdp
year <- npregbw$year
npregbw_1 <- npregbw(formula = gdp ~ ordered(year))
summary(npregbw_1)
npregbw_2 <- npregbw(xdat = ordered(year), ydat = gdp)
summary(npregbw_2)
# Kernel Regression Bandwidth Selection with Mixed Data Types Use npregbw (np) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished