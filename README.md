# flowable-ui-rest-docker-compose
A simple docker compose file to run Flowable Rest and Flowable UI with same postgresql.
# How to run it
1. Change directory to location of yml file
2. run: docker-compose -f ui-rest-postgres.yml up
3. Then access flowable ui at: http://localhost:8090/flowable-ui/ with default username/password: admin/test
4. Access swagger ui at: http://localhost:8089/flowable-rest/docs
