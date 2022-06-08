# interview_sql_tests
Abibulla Gulzada 
phone number: 8-708-181-1337
Task1
-- SELECT DISTINCT Passenger.id, Passenger.name as PASSENGER_NAME, 
-- Trip.plane, Company.name AS COMPANY_NAME FROM Trip, Passenger, Company
-- WHERE Trip.plane = "Boeing" AND 
-- Company.name ="air_France";
Task2
-- SELECT trip, COUNT(passenger) as quantity 
-- FROM  Pass_in_trip
-- GROUP BY  trip;
Task3
-- SELECT
-- name, COUNT(*)
-- FROM Passenger
-- GROUP BY name
-- HAVING COUNT(*)>1
-- ORDER BY COUNT(*) DESC;
