1. Mo file config.json
2. Thay đổi cấu hình để phù hợp với hệ cơ sở dữ liệu
3. //MSSQL
  // "Provider": "mssql",
  // "ConnectionString": "Data Source=(local);Initial Catalog=WorkflowServer;Integrated Security=False;User ID=sa;Password=1;"

  //PostgreSQL
  //"Provider": "postgresql",
  //"ConnectionString": "User ID=postgres;Password=1;Host=localhost;Port=5432;Database=WorkflowServer;"

  //Oracle
  //"Provider": "oracle",
  //"ConnectionString": "Data Source=(DESCRIPTION=(ADDRESS_LIST=(ADDRESS=(COMMUNITY = tcp.world)(PROTOCOL = TCP)(Host = MyHost)(Port = 1521)))(CONNECT_DATA=(SID=MyOracleSID)));User ID=myUsername;Password=myPassword;"

  //MySql
  //"Provider": "mysql",
  //"ConnectionString": "server=127.0.0.1;uid=root;pwd=myPassword;database=WorkflowServer"

  //MongoDB or Cosmos DB
  "Provider": "mongodb",
  "ConnectionString": "mongodb://localhost:27017/WorkflowServer"
4.Mở terminal 
  nhập lệnh
  pip install facebook_scaper
  .\start.bat
