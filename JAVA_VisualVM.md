# 실행 명령어
>java   -Dcom.sun.management.jmxremote=true \\
        -Dcom.sun.management.jmxremote.port=**8180** \\
        -Dcom.sun.management.jmxremote.authenticate=false \\
        -Dcom.sun.management.jmxremote.ssl=false \\
        -Djava.rmi.server.hostname=**서버아이피** \\<br>
        -Dcom.sun.management.jmxremote.rmi.port=**8180** \\
        -Xmx5g \\
        -Xms5g \\
        -Dspring.profiles.active=prod \\
        -jar program.jar 
