FROM nuwanbando/javabase:v2

RUN mkdir wso2 

COPY packs/wso2analytics-apim-2.0.0-beta2.zip wso2/

RUN cd wso2/ && \
        unzip wso2analytics-apim-2.0.0-beta2.zip


CMD ["sh", "/wso2/wso2analytics-apim-2.0.0-beta2/bin/wso2server.sh"]

EXPOSE 9764
EXPOSE 9444
EXPOSE 7712
EXPOSE 7612