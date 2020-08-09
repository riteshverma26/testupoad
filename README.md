# testupoad

### Table Structure 4 for Complex DataTypes
#### create table person_avro(person_id int, person_name string, person_address string, person_zip int, person_phone string, person_age int, person_birthdate string, person_healthinsurancepolicy boolean, person_healthinsurancepolicyvalue double, department string, person_salary float, person_height BIGINT, person_country ARRAY<string>, doctor_fee INT) STORED AS AVRO LOCATION '/tmp/person_avro';
