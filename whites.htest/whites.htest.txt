# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# White test for heteroscedasticity in time-series VAR model Use whites.htest (het.test) With (In) R Software
install.packages("vars")
install.packages("remotes")
remotes::install_github("cran/het.test")
library("vars")
library("het.test")
# Estimation White test for heteroscedasticity in time-series VAR model Use whites.htest (het.test) With (In) R Software
whites.htest = read.csv("https://raw.githubusercontent.com/timbulwidodostp/whites.htest/main/whites.htest/whites.htest.csv", sep = ";")
VAR <- VAR(whites.htest)
whites.htest <- whites.htest(VAR)
whites.htest
# White test for heteroscedasticity in time-series VAR model Use whites.htest (het.test) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished