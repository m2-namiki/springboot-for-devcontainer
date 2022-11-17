FROM amazoncorretto:11-al2-jdk

ENV PACKAGES="git tar"

# yumのアップデートとパッケージのインストール
RUN yum -y update && \
    yum install -y ${PACKAGES}
