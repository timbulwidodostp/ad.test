# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Anderson-Darling k-Sample Test Use ad.test (kSamples) With (In) R Software
install.packages("kSamples")
library("kSamples")
# Estimate Anderson-Darling k-Sample Test Use ad.test (kSamples) With (In) R Software
ad.test = read.csv("https://raw.githubusercontent.com/timbulwidodostp/ad.test/main/ad.test/ad.test.csv",sep = ";")
ad.test_1 <- ad.test$ad.test_1
ad.test_2 <- ad.test$ad.test_2
ad.test_3 <- ad.test$ad.test_3
ad.test_4 <- ad.test$ad.test_4
ad.test <- ad.test(ad.test_1, ad.test_2, ad.test_3, ad.test_4)
ad.test
# Anderson-Darling k-Sample Test Use ad.test (kSamples) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished