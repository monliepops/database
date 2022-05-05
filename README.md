# test.yaml
test-repo
                  main-sag:
		    url: postgres://pghero:p0stgres4HERO@psql-sag-sit.postgres.database.azure.com:5432/postgres?sslmode=require
		  mxcrmpdb:
		    url: postgres://pghero:p0stgres4HERO@psql-sag-sit.postgres.database.azure.com:5432/mxcrmpdb?sslmode=require
		    capture_query_stats: main-sag
		  mxcbodb:
		    url: postgres://pghero:p0stgres4HERO@psql-sag-sit.postgres.database.azure.com:5432/mxcbodb?sslmode=require
		    capture_query_stats: main-sag
