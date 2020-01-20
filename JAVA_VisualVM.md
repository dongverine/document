# 실행 명령어
java   -Dcom.sun.management.jmxremote=true \\<br>
        -Dcom.sun.management.jmxremote.port=**8180** \\<br>
        -Dcom.sun.management.jmxremote.authenticate=false \\<br>
        -Dcom.sun.management.jmxremote.ssl=false \\
        -Djava.rmi.server.hostname=**서버아이피** \\<br>
        -Dcom.sun.management.jmxremote.rmi.port=**8180** \\<br>
        -Xmx5g \\<br>
        -Xms5g \\<br>
        -Dspring.profiles.active=prod \\<br>
        -jar program.jar <br>
