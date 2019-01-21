# Problems
问题收集
mac 安装mysql-client:
    错误信息:
        ld: library not found for -lssl;
        error: command 'gcc' failed with exit status 1
    解决:
        brew install openssl;
        export LIBRARY_PATH=$LIBRARY_PATH:/usr/local/opt/openssl/lib/
