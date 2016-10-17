FROM nuwanbando/javabase:v2

RUN mkdir wso2 

COPY packs/wso2am-2.0.0.zip wso2/

RUN cd wso2/ && \
        unzip wso2am-2.0.0.zip

COPY apim/api-manager.xml /wso2/wso2am-2.0.0/repository/conf/api-manager.xml


CMD ["sh", "/wso2/wso2am-2.0.0/bin/wso2server.sh"]

EXPOSE 9763
EXPOSE 9443
EXPOSE 8280
EXPOSE 8243