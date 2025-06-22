# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Threshold Selection and Uncertainty for Extreme Value Analysis Use ithresh (threshr) With (In) R Software
install.packages("threshr")
library("threshr")
ithresh = read.csv("https://raw.githubusercontent.com/timbulwidodostp/ithresh/main/ithresh/ithresh.csv",sep = ";")
# Estimation Threshold Selection and Uncertainty for Extreme Value Analysis Use ithresh (threshr) With (In) R Software
ithresh <- ithresh$x
quantile <- quantile(ithresh, probs = seq(0, 0.9, by = 0.05))
ithresh <- ithresh(data = ithresh, u_vec = quantile)
summary(ithresh)
plot(ithresh)
# Threshold Selection and Uncertainty for Extreme Value Analysis Use ithresh (threshr) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished