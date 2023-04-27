# ARG USER=spiffs
# ARG UID=1000

# FROM espressif/idf:v4.4.1
FROM espressif/idf:release-v5.1

# ARG USER
# ARG UID

# RUN ["/bin/dash","-c","\
#     addgroup \
#     --gid ${UID} "${USER}" \
#     && adduser \
#     --disabled-password \
#     --gecos \"\" \
#     --ingroup \"${USER}\" \
#     --uid ${UID} \
#     \"${USER}\" \
#     && usermod \
#     --append \
#     --groups \"dialout,plugdev\" \
#     \"${USER}\" \
#     "]

RUN echo "source /opt/esp/idf/export.sh" >> /root/.bashrc