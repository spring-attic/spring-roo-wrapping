
Db2Expresss JDBC driver must be downloaded manually from hhttp://www-01.ibm.com/support/docview.wss?uid=swg21363866 before build the wrapping.
Wrapping is internally configured for use com.ibm.db2.jcc.DB2Driver driver, use another at your own risk.
Then run lib/install-lib.sh to install the driver in your maven local repository.
Finally build the wrapping with maven.
