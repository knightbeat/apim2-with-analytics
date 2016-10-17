FROM nuwanbando/javabase:v2

RUN mkdir wso2 

COPY packs/wso2am-analytics-2.0.0.zip wso2/

RUN cd wso2/ && \
        unzip wso2am-analytics-2.0.0.zip


CMD ["sh", "/wso2/wso2am-analytics-2.0.0/bin/wso2server.sh"]

EXPOSE 9764
EXPOSE 9444
EXPOSE 7712
EXPOSE 7612