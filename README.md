# docker-gradle-phantomjs

This docker contains gradle wrapper already downloaded and  set of jars cached for running cucumber tests.

docker run -t -v "[YOUR_APP_REPOSITORY]":"/app" barrymac/phantom-1.9.8 gradle cucumber
