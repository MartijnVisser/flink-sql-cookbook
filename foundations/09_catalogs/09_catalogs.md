CREATE CATALOG postgres WITH (
    'type'='jdbc',
    'property-version'='1',
    'base-url'='jdbc:postgresql://localhost:5438/',
    'default-database'='postgres',
    'username'='postgres',
    'password'='postgres'
);