FROM mysql:5.7

ENV DATABASE_URI=mysql+pymysql://root:password@mysql:3306/users SECRET_KEY=password

COPY ./Create.sql /docker-entrypoint-initdb.d
