QueryTools

Compatible with Sphinx Search and Manticore Search

Options

      ConnectionStrings__DefaultConnection: "Host=127.0.0.1;Port=9306;Command Timeout=0"

      ServerConfig__BasePath: "/mysql"

      Kestrel__Endpoints__Http__Url: http://0.0.0.0:9090

      Kestrel__Endpoints__Https__Url: http://0.0.0.0:9433

Example
	docker run -it mysqlquerytoolswebapp -p 9433:9433 -e "ConnectionStrings__DefaultConnection"="Host=host.docker.internal;Port=9306;Command Timeout=0"
