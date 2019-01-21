# Problems
问题收集<br>
'mac 安装mysql-client:'<br>
>>>>错误信息:<br>
>>>>>>>>ld: library not found for -lssl;<br>
>>>>>>>>error: command 'gcc' failed with exit status 1<br>
>>>>解决:<br>
>>>>>>>>brew install openssl;<br>
>>>>>>>>export LIBRARY_PATH=$LIBRARY_PATH:/usr/local/opt/openssl/lib/<br>
