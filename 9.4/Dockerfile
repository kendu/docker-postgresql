#
#       .
#        ":"
#      ___:____     |"\/"|
#    ,'        `.    \  /
#    |  O        \___/  |
#  ~^~^~^~^~^~^~^~^~^~^~^~^~

#The postgresql container

FROM postgres:9.4
MAINTAINER Kendu DevOps Team <devops@kendu.si>

# Set locales.
RUN localedef -i sl_SI -c -f UTF-8 -A /usr/share/locale/locale.alias sl_SI.UTF-8
ENV LANG sl_SI.UTF-8
