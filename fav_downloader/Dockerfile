FROM busybox
WORKDIR /opt/fd
COPY ./fav_downloader.sh /opt/fd
RUN chmod +x /opt/fd/fav_downloader.sh
ENTRYPOINT [ "sh", "/opt/fd/fav_downloader.sh" ] 
