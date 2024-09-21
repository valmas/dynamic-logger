#
# Copyright 2023 European Union. All rights reserved.
# European Union PROPRIETARY/CONFIDENTIAL.
#
ARG BASE_IMAGE_REGISTRY
FROM ${BASE_IMAGE_REGISTRY}ubi8/openjdk-17:1.18

COPY target/*.jar app.jar
ENTRYPOINT ["java", "-jar", "app.jar"]