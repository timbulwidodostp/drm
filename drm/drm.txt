# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Fitting dose-response models Use drm (drc) With (In) R Software
install.packages("drc")
library("drc")
drm = read.csv("https://raw.githubusercontent.com/timbulwidodostp/drm/main/drm/drm.csv",sep = ";")
# Estimation Fitting dose-response models Use drm (drc) With (In) R Software
drm <- drm(Y~X, ID, data = drm, fct = LL.4(), pmodels = data.frame(DUMMY, 1, 1, DUMMY))
summary(drm)
# Fitting dose-response models Use drm (drc) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished