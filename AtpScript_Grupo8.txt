FLUSH QUERY CACHE;
SELECT "Grupo 8 | André Silvestre, Diogo Catarino, Francisco Gomes, Rita Matos";

use atp

DROP TABLE IF EXISTS countries;
CREATE TABLE countries (Country_Name varchar(100), Country_Code varchar(2), PRIMARY KEY(Country_Name));
LOAD DATA INFILE "c:/data/atp/countries_net.csv" INTO TABLE countries FIELDS TERMINATED BY ',' ENCLOSED BY '"' LINES TERMINATED BY '\n' IGNORE 1 LINES;

UPDATE atp SET Born_Country = "Côte d'Ivoire" WHERE LTRIM(RTRIM(Born_Country)) = "Abidjan";
UPDATE atp SET Born_Country = "Mexico" WHERE LTRIM(RTRIM(Born_Country)) = "Acapulco";
UPDATE atp SET Born_Country = "Ghana" WHERE LTRIM(RTRIM(Born_Country)) = "Accra";
UPDATE atp SET Born_Country = "Germany" WHERE LTRIM(RTRIM(Born_Country)) = "Achim";
UPDATE atp SET Born_Country = "Spain" WHERE LTRIM(RTRIM(Born_Country)) = "Adeje";
UPDATE atp SET Born_Country = "Australia" WHERE LTRIM(RTRIM(Born_Country)) = "Adelaide";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "Aix-en-Provence";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "Ajaccio";
UPDATE atp SET Born_Country = "Kazakhstan" WHERE LTRIM(RTRIM(Born_Country)) = "Aktau";
UPDATE atp SET Born_Country = "United Kingdom" WHERE LTRIM(RTRIM(Born_Country)) = "Birmingham, AL";
UPDATE atp SET Born_Country = "Italy" WHERE LTRIM(RTRIM(Born_Country)) = "Alatri";
UPDATE atp SET Born_Country = "Egypt" WHERE LTRIM(RTRIM(Born_Country)) = "Alexandria";
UPDATE atp SET Born_Country = "Spain" WHERE LTRIM(RTRIM(Born_Country)) = "Algemesi";
UPDATE atp SET Born_Country = "Kazakhstan" WHERE LTRIM(RTRIM(Born_Country)) = "Almaty";
UPDATE atp SET Born_Country = "Netherlands" WHERE LTRIM(RTRIM(Born_Country)) = "Alphen aan den Rijn";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Altadena";
UPDATE atp SET Born_Country = "Korea, Democratic People's Republic of" WHERE LTRIM(RTRIM(Born_Country)) = "AN SUNG";
UPDATE atp SET Born_Country = "Italy" WHERE LTRIM(RTRIM(Born_Country)) = "Ancona";
UPDATE atp SET Born_Country = "Italy" WHERE LTRIM(RTRIM(Born_Country)) = "Andong";
UPDATE atp SET Born_Country = "Korea, Republic of" WHERE LTRIM(RTRIM(Born_Country)) = "Anseong";
UPDATE atp SET Born_Country = "Madagascar" WHERE LTRIM(RTRIM(Born_Country)) = "Antananarivo";
UPDATE atp SET Born_Country = "Mexico" WHERE LTRIM(RTRIM(Born_Country)) = "Apizaco";
UPDATE atp SET Born_Country = "Argentina" WHERE LTRIM(RTRIM(Born_Country)) = "San Francisco (Cordoba), ARG";
UPDATE atp SET Born_Country = "Argentina" WHERE LTRIM(RTRIM(Born_Country)) = "Tandil, Buenos Aires, Argentin";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Arlington";
UPDATE atp SET Born_Country = "Germany" WHERE LTRIM(RTRIM(Born_Country)) = "Aschaffenburg";
UPDATE atp SET Born_Country = "Bulgaria" WHERE LTRIM(RTRIM(Born_Country)) = "Asenovgrad";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Atlanta";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Atlanta Ga";
UPDATE atp SET Born_Country = "New Zealand" WHERE LTRIM(RTRIM(Born_Country)) = "Auckland";
UPDATE atp SET Born_Country = "Australia" WHERE LTRIM(RTRIM(Born_Country)) = "Gympie, Queensland, AUS";
UPDATE atp SET Born_Country = "Australia" WHERE LTRIM(RTRIM(Born_Country)) = "Symmons, Plains,Tasmania,Aust.";
UPDATE atp SET Born_Country = "Australia" WHERE LTRIM(RTRIM(Born_Country)) = "Launceston, Tasmania, Aust..";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Austin";
UPDATE atp SET Born_Country = "Romania" WHERE LTRIM(RTRIM(Born_Country)) = "Bacau";
UPDATE atp SET Born_Country = "Germany" WHERE LTRIM(RTRIM(Born_Country)) = "Bad Hersfeld";
UPDATE atp SET Born_Country = "Argentina" WHERE LTRIM(RTRIM(Born_Country)) = "Bahia Blanca";
UPDATE atp SET Born_Country = "Mexico" WHERE LTRIM(RTRIM(Born_Country)) = "Baja";
UPDATE atp SET Born_Country = "Argentina" WHERE LTRIM(RTRIM(Born_Country)) = "Balcarce";
UPDATE atp SET Born_Country = "Thailand" WHERE LTRIM(RTRIM(Born_Country)) = "Bangkok";
UPDATE atp SET Born_Country = "Belarus" WHERE LTRIM(RTRIM(Born_Country)) = "Barakovichi";
UPDATE atp SET Born_Country = "Spain" WHERE LTRIM(RTRIM(Born_Country)) = "Barbastro";


UPDATE atp SET Born_Country = "Spain" WHERE LTRIM(RTRIM(Born_Country)) LIKE "%Barcelona%";

UPDATE atp SET Born_Country = "Venezuela, Bolivarian Republic of" WHERE LTRIM(RTRIM(Born_Country)) = "Barquisimeto";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "BASTIA";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "Bayonne";
UPDATE atp SET Born_Country = "Ireland" WHERE LTRIM(RTRIM(Born_Country)) = "Belfast";
UPDATE atp SET Born_Country = "Serbia" WHERE LTRIM(RTRIM(Born_Country)) = "Belgrade";
UPDATE atp SET Born_Country = "Brazil" WHERE LTRIM(RTRIM(Born_Country)) = "Belo Horizonte";
UPDATE atp SET Born_Country = "India" WHERE LTRIM(RTRIM(Born_Country)) = "Bengaluru";
UPDATE atp SET Born_Country = "Germany" WHERE LTRIM(RTRIM(Born_Country)) = "Bergisch - Gladbach";
UPDATE atp SET Born_Country = "Germany" WHERE LTRIM(RTRIM(Born_Country)) = "Berlin";
UPDATE atp SET Born_Country = "Switzerland" WHERE LTRIM(RTRIM(Born_Country)) = "Bern";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "Biarritz";
UPDATE atp SET Born_Country = "Switzerland" WHERE LTRIM(RTRIM(Born_Country)) = "Bienne";
UPDATE atp SET Born_Country = "United Kingdom" WHERE LTRIM(RTRIM(Born_Country)) = "Birmingham";
UPDATE atp SET Born_Country = "Netherlands" WHERE LTRIM(RTRIM(Born_Country)) = "Blaricum";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Boca Raton";
UPDATE atp SET Born_Country = "Colombia" WHERE LTRIM(RTRIM(Born_Country)) = "Bogota";

UPDATE atp SET Born_Country = "Bolivia, Plurinational State of" WHERE LTRIM(RTRIM(Born_Country)) LIKE "%Bolivia%";

UPDATE atp SET Born_Country = "Italy" WHERE LTRIM(RTRIM(Born_Country)) = "Bologna";
UPDATE atp SET Born_Country = "Germany" WHERE LTRIM(RTRIM(Born_Country)) = "Bonn";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "Bordeaux";

UPDATE atp SET Born_Country = "Bosnia and Herzegovina" WHERE LTRIM(RTRIM(Born_Country)) LIKE "%Bosnia%";
UPDATE atp SET Born_Country = "Bosnia and Herzegovina" WHERE LTRIM(RTRIM(Born_Country)) LIKE "%Bosnia & Herzegovina%";
UPDATE atp SET Born_Country = "Bosnia and Herzegovina" WHERE LTRIM(RTRIM(Born_Country)) LIKE "%Bosnia-Herzegovina%";

UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Boston";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "Boulogne-Sur-Mer";
UPDATE atp SET Born_Country = "United Kingdom" WHERE LTRIM(RTRIM(Born_Country)) = "Box Hill";
UPDATE atp SET Born_Country = "Brazil" WHERE LTRIM(RTRIM(Born_Country)) = "Marechal Candido Rondon, BRA";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Bradenton";
UPDATE atp SET Born_Country = "Argentina" WHERE LTRIM(RTRIM(Born_Country)) = "Bragado";

UPDATE atp SET Born_Country = "Brazil" WHERE LTRIM(RTRIM(Born_Country)) LIKE "%Brasil%";

UPDATE atp SET Born_Country = "Brazil" WHERE LTRIM(RTRIM(Born_Country)) = "Brasilia";
UPDATE atp SET Born_Country = "Slovakia" WHERE LTRIM(RTRIM(Born_Country)) = "Bratislava";
UPDATE atp SET Born_Country = "Belgium" WHERE LTRIM(RTRIM(Born_Country)) = "Bree";
UPDATE atp SET Born_Country = "Germany" WHERE LTRIM(RTRIM(Born_Country)) = "Bremen";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "BREST";
UPDATE atp SET Born_Country = "Barbados" WHERE LTRIM(RTRIM(Born_Country)) = "Bridgetown";
UPDATE atp SET Born_Country = "Australia" WHERE LTRIM(RTRIM(Born_Country)) = "Brisbane";
UPDATE atp SET Born_Country = "Czech Republic" WHERE LTRIM(RTRIM(Born_Country)) = "Brno";
UPDATE atp SET Born_Country = "Romania" WHERE LTRIM(RTRIM(Born_Country)) = "Bucharest";
UPDATE atp SET Born_Country = "Romania" WHERE LTRIM(RTRIM(Born_Country)) = "Bucuresti";
UPDATE atp SET Born_Country = "Hungary" WHERE LTRIM(RTRIM(Born_Country)) = "Budapest";


UPDATE atp SET Born_Country = "Argentina" WHERE LTRIM(RTRIM(Born_Country)) LIKE "%Buenos Aires%";


UPDATE atp SET Born_Country = "Spain" WHERE LTRIM(RTRIM(Born_Country)) = "Burgos";
UPDATE atp SET Born_Country = "Italy" WHERE LTRIM(RTRIM(Born_Country)) = "Busto Arsizio";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Irvine, CA";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Newport Beach, CA USA";
UPDATE atp SET Born_Country = "Philippines" WHERE LTRIM(RTRIM(Born_Country)) = "Cagayan de Oro City";
UPDATE atp SET Born_Country = "Canada" WHERE LTRIM(RTRIM(Born_Country)) = "Calgary";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Calhoun";


UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) LIKE "%California%";


UPDATE atp SET Born_Country = "Cambodia" WHERE LTRIM(RTRIM(Born_Country)) = "Battambang, Camboda";
UPDATE atp SET Born_Country = "United Kingdom" WHERE LTRIM(RTRIM(Born_Country)) = "Campbelltown";
UPDATE atp SET Born_Country = "Brazil" WHERE LTRIM(RTRIM(Born_Country)) = "Campinas";
UPDATE atp SET Born_Country = "Italy" WHERE LTRIM(RTRIM(Born_Country)) = "Campobasso";
UPDATE atp SET Born_Country = "Canada" WHERE LTRIM(RTRIM(Born_Country)) = "Montreal, Canda";
UPDATE atp SET Born_Country = "Argentina" WHERE LTRIM(RTRIM(Born_Country)) = "Capital Federal";
UPDATE atp SET Born_Country = "Venezuela, Bolivarian Republic of" WHERE LTRIM(RTRIM(Born_Country)) = "Caracas";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "Carcassonne";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "carhaix plougher";
UPDATE atp SET Born_Country = "Tunisia" WHERE LTRIM(RTRIM(Born_Country)) = "Cartago";
UPDATE atp SET Born_Country = "Italy" WHERE LTRIM(RTRIM(Born_Country)) = "Casalmaggiore";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Chandler Arizona";
UPDATE atp SET Born_Country = "Taiwan, Province of China" WHERE LTRIM(RTRIM(Born_Country)) = "Changhwa";
UPDATE atp SET Born_Country = "Argentina" WHERE Born_Country LIKE "Chascom%";
UPDATE atp SET Born_Country = "United Kingdom" WHERE LTRIM(RTRIM(Born_Country)) = "Chelmsford";
UPDATE atp SET Born_Country = "India" WHERE LTRIM(RTRIM(Born_Country)) = "Chennai";
UPDATE atp SET Born_Country = "Ukraine" WHERE LTRIM(RTRIM(Born_Country)) = "Chernivtsi";
UPDATE atp SET Born_Country = "United Kingdom" WHERE LTRIM(RTRIM(Born_Country)) = "Chichester";


UPDATE atp SET Born_Country = "Taiwan, Province of China" WHERE LTRIM(RTRIM(Born_Country)) LIKE "%Chinese%";


UPDATE atp SET Born_Country = "Moldova, Republic of" WHERE LTRIM(RTRIM(Born_Country)) = "Chisinau";
UPDATE atp SET Born_Country = "Taiwan, Province of China" WHERE LTRIM(RTRIM(Born_Country)) = "Chunghua";
UPDATE atp SET Born_Country = "Switzerland" WHERE LTRIM(RTRIM(Born_Country)) = "Chur";
UPDATE atp SET Born_Country = "Italy" WHERE Born_Country LIKE "Ciri%";


UPDATE atp SET Born_Country = "Argentina" WHERE Born_Country LIKE "%noma de Buenos";

UPDATE atp SET Born_Country = "Spain" WHERE LTRIM(RTRIM(Born_Country)) = "Ciutadella de Menorca";
UPDATE atp SET Born_Country = "Italy" WHERE LTRIM(RTRIM(Born_Country)) = "Civitavecchia";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "Clichy";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Boulder, CO";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Colchester";
UPDATE atp SET Born_Country = "Germany" WHERE LTRIM(RTRIM(Born_Country)) = "Cologne";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Colorado Springs";
UPDATE atp SET Born_Country = "Italy" WHERE LTRIM(RTRIM(Born_Country)) = "Como";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Concord";
UPDATE atp SET Born_Country = "Romania" WHERE LTRIM(RTRIM(Born_Country)) = "Constanta";
UPDATE atp SET Born_Country = "Spain" WHERE LTRIM(RTRIM(Born_Country)) = "Cordoba";
UPDATE atp SET Born_Country = "Argentina" WHERE LTRIM(RTRIM(Born_Country)) = "Corrientes";
UPDATE atp SET Born_Country = "Ukraine" WHERE LTRIM(RTRIM(Born_Country)) = "Simferopol, Crimea";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Avon, CT";
UPDATE atp SET Born_Country = "Romania" WHERE LTRIM(RTRIM(Born_Country)) = "Cugir";
UPDATE atp SET Born_Country = "Italy" WHERE LTRIM(RTRIM(Born_Country)) = "Cuneo";
UPDATE atp SET Born_Country = "Brazil" WHERE LTRIM(RTRIM(Born_Country)) = "Curitiba";
UPDATE atp SET Born_Country = "Czech Republic" WHERE LTRIM(RTRIM(Born_Country)) = "Jindrichuv Hradec, Cz Republic";
UPDATE atp SET Born_Country = "Czech Republic" WHERE LTRIM(RTRIM(Born_Country)) = "Bystrice nad Pernstejnem, CZE";
UPDATE atp SET Born_Country = "Czech Republic" WHERE LTRIM(RTRIM(Born_Country)) = "Hradec Kvalove, Czech Rep.";
UPDATE atp SET Born_Country = "Czech Republic" WHERE LTRIM(RTRIM(Born_Country)) = "Prague, Czech Repbulic";
UPDATE atp SET Born_Country = "Czech Republic" WHERE LTRIM(RTRIM(Born_Country)) = "Valasske Mezirici, Czech.";

UPDATE atp SET Born_Country = "Czech Republic" WHERE LTRIM(RTRIM(Born_Country)) LIKE "%Czech Rep.%";
UPDATE atp SET Born_Country = "Slovakia" WHERE LTRIM(RTRIM(Born_Country)) LIKE "%Czechoslovakia%";
UPDATE atp SET Born_Country = "Spain" WHERE Born_Country LIKE "%rdoba";
UPDATE atp SET Born_Country = "France" WHERE Born_Country LIKE "%ret";


UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Washington, D.C.";
UPDATE atp SET Born_Country = "Korea, Republic of" WHERE LTRIM(RTRIM(Born_Country)) = "Daejeon";
UPDATE atp SET Born_Country = "China" WHERE LTRIM(RTRIM(Born_Country)) = "Dalian";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Davis";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Washington, DC";
UPDATE atp SET Born_Country = "India" WHERE LTRIM(RTRIM(Born_Country)) = "Delhi";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Des Moines";
UPDATE atp SET Born_Country = "Belgium" WHERE LTRIM(RTRIM(Born_Country)) = "Diest";
UPDATE atp SET Born_Country = "Bulgaria" WHERE LTRIM(RTRIM(Born_Country)) = "Dimitrovgrad";
UPDATE atp SET Born_Country = "Netherlands" WHERE LTRIM(RTRIM(Born_Country)) = "Dirksland";
UPDATE atp SET Born_Country = "Ukraine" WHERE LTRIM(RTRIM(Born_Country)) = "dnepropetrovsk";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Does Moines";
UPDATE atp SET Born_Country = "Dominican Republic" WHERE LTRIM(RTRIM(Born_Country)) = "Santo Domingo, Dominican Rep.";
UPDATE atp SET Born_Country = "Ukraine" WHERE LTRIM(RTRIM(Born_Country)) = "Donetsk";
UPDATE atp SET Born_Country = "United Arab Emirates" WHERE LTRIM(RTRIM(Born_Country)) = "Dubai";
UPDATE atp SET Born_Country = "Ireland" WHERE LTRIM(RTRIM(Born_Country)) = "dublin";
UPDATE atp SET Born_Country = "Germany" WHERE LTRIM(RTRIM(Born_Country)) = "Duesseldorf";
UPDATE atp SET Born_Country = "Germany" WHERE LTRIM(RTRIM(Born_Country)) = "Duisburg";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "Dunkerque";
UPDATE atp SET Born_Country = "South Africa" WHERE LTRIM(RTRIM(Born_Country)) = "Durban";


UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) LIKE "%USA%";


UPDATE atp SET Born_Country = "South Africa" WHERE LTRIM(RTRIM(Born_Country)) = "Edenvale";


UPDATE atp SET Born_Country = "Sweden" WHERE Born_Country LIKE "Eksj%";


UPDATE atp SET Born_Country = "Spain" WHERE LTRIM(RTRIM(Born_Country)) = "Elche";


UPDATE atp SET Born_Country = "United Kingdom" WHERE LTRIM(RTRIM(Born_Country)) LIKE "%England%";


UPDATE atp SET Born_Country = "Italy" WHERE LTRIM(RTRIM(Born_Country)) = "Erice";
UPDATE atp SET Born_Country = "Iran, Islamic Republic of" WHERE LTRIM(RTRIM(Born_Country)) = "Esfahan";
UPDATE atp SET Born_Country = "Germany" WHERE LTRIM(RTRIM(Born_Country)) = "Essen";
UPDATE atp SET Born_Country = "United Kingdom" WHERE LTRIM(RTRIM(Born_Country)) = "Southend-on-sea, Essex";
UPDATE atp SET Born_Country = "Ukraine" WHERE LTRIM(RTRIM(Born_Country)) = "Evpatoria";
UPDATE atp SET Born_Country = "United Kingdom" WHERE LTRIM(RTRIM(Born_Country)) = "Exeter";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Fargo";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Miami, FL";
UPDATE atp SET Born_Country = "Switzerland" WHERE LTRIM(RTRIM(Born_Country)) = "Flawil";
UPDATE atp SET Born_Country = "Italy" WHERE LTRIM(RTRIM(Born_Country)) = "Florence";


UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) LIKE "%Florida%";


UPDATE atp SET Born_Country = "Germany" WHERE LTRIM(RTRIM(Born_Country)) = "Forchheim";
UPDATE atp SET Born_Country = "Italy" WHERE LTRIM(RTRIM(Born_Country)) = "Formia";
UPDATE atp SET Born_Country = "Switzerland" WHERE LTRIM(RTRIM(Born_Country)) = "Frauenfeld";
UPDATE atp SET Born_Country = "Denmark" WHERE LTRIM(RTRIM(Born_Country)) = "Frederiksberg";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "Frejus";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Fresno";
UPDATE atp SET Born_Country = "Germany" WHERE LTRIM(RTRIM(Born_Country)) = "Friedrichshafen";
UPDATE atp SET Born_Country = "Japan" WHERE LTRIM(RTRIM(Born_Country)) = "fukuoka";
UPDATE atp SET Born_Country = "Japan" WHERE LTRIM(RTRIM(Born_Country)) = "Fukushima";
UPDATE atp SET Born_Country = "Portugal" WHERE LTRIM(RTRIM(Born_Country)) = "Funchal";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Atlanta, GA";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Galveston";
UPDATE atp SET Born_Country = "Korea, Republic of" WHERE LTRIM(RTRIM(Born_Country)) = "Gangwonto";
UPDATE atp SET Born_Country = "Russian Federation" WHERE LTRIM(RTRIM(Born_Country)) = "Gatchina";
UPDATE atp SET Born_Country = "South Africa" WHERE LTRIM(RTRIM(Born_Country)) = "Gauteng";
UPDATE atp SET Born_Country = "Switzerland" WHERE LTRIM(RTRIM(Born_Country)) = "Geneva";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Genova";
UPDATE atp SET Born_Country = "Belgium" WHERE LTRIM(RTRIM(Born_Country)) = "Gent";
UPDATE atp SET Born_Country = "Germany" WHERE LTRIM(RTRIM(Born_Country)) = "Garmisch-Patenkirchen, GER";
UPDATE atp SET Born_Country = "Spain" WHERE LTRIM(RTRIM(Born_Country)) = "Gijon";
UPDATE atp SET Born_Country = "Burundi" WHERE LTRIM(RTRIM(Born_Country)) = "Gitega";
UPDATE atp SET Born_Country = "Australia" WHERE LTRIM(RTRIM(Born_Country)) = "Gold Coast";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "Gonesse";
UPDATE atp SET Born_Country = "Sweden" WHERE LTRIM(RTRIM(Born_Country)) = "Gothenburg";
UPDATE atp SET Born_Country = "Bahamas" WHERE LTRIM(RTRIM(Born_Country)) = "Freeport, Grand Bahamas";
UPDATE atp SET Born_Country = "Austria" WHERE LTRIM(RTRIM(Born_Country)) = "Graz";


UPDATE atp SET Born_Country = "United Kingdom" WHERE LTRIM(RTRIM(Born_Country)) LIKE "%Great Britain%";


UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Greenbrae";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "Grenoble";
UPDATE atp SET Born_Country = "Netherlands" WHERE LTRIM(RTRIM(Born_Country)) = "Groningen";


UPDATE atp SET Born_Country = "Germany" WHERE Born_Country LIKE "Gr%" AND Born_Country LIKE "%felfing";


UPDATE atp SET Born_Country = "Italy" WHERE LTRIM(RTRIM(Born_Country)) = "Guastalla";
UPDATE atp SET Born_Country = "Guatemala" WHERE LTRIM(RTRIM(Born_Country)) = "Guatemala City";
UPDATE atp SET Born_Country = "Ecuador" WHERE LTRIM(RTRIM(Born_Country)) = "Guayaquil";
UPDATE atp SET Born_Country = "Portugal" WHERE LTRIM(RTRIM(Born_Country)) = "Guimaraes";
UPDATE atp SET Born_Country = "Netherlands" WHERE LTRIM(RTRIM(Born_Country)) = "Haarlem";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Hackensack";
UPDATE atp SET Born_Country = "Israel" WHERE LTRIM(RTRIM(Born_Country)) = "Haifa";
UPDATE atp SET Born_Country = "Austria" WHERE LTRIM(RTRIM(Born_Country)) = "Hall in Tirol";
UPDATE atp SET Born_Country = "Germany" WHERE LTRIM(RTRIM(Born_Country)) = "Hamburg";
UPDATE atp SET Born_Country = "United Kingdom" WHERE LTRIM(RTRIM(Born_Country)) = "Hampstead";
UPDATE atp SET Born_Country = "Zimbabwe" WHERE LTRIM(RTRIM(Born_Country)) = "Harare";
UPDATE atp SET Born_Country = "India" WHERE LTRIM(RTRIM(Born_Country)) = "Khanpur Khurd,Jhajjar,Haryana";
UPDATE atp SET Born_Country = "United Kingdom" WHERE LTRIM(RTRIM(Born_Country)) = "Hatfield";
UPDATE atp SET Born_Country = "Cuba" WHERE LTRIM(RTRIM(Born_Country)) = "Havana";
UPDATE atp SET Born_Country = "China" WHERE LTRIM(RTRIM(Born_Country)) = "HEILONGJIANG";
UPDATE atp SET Born_Country = "Finland" WHERE LTRIM(RTRIM(Born_Country)) = "Helsinki";
UPDATE atp SET Born_Country = "Cuba" WHERE LTRIM(RTRIM(Born_Country)) = "Hershey";
UPDATE atp SET Born_Country = "Netherlands" WHERE LTRIM(RTRIM(Born_Country)) = "Heythuysen";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Honolulu, HI";
UPDATE atp SET Born_Country = "United Kingdom" WHERE LTRIM(RTRIM(Born_Country)) = "High Wycombe";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Hilton Head Island";
UPDATE atp SET Born_Country = "Sweden" WHERE LTRIM(RTRIM(Born_Country)) = "Hjo";


UPDATE atp SET Born_Country = "Czech Republic" WHERE Born_Country LIKE "Hodon%";


UPDATE atp SET Born_Country = "Netherlands" WHERE LTRIM(RTRIM(Born_Country)) = "Permerand, Holland";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Holtsville";
UPDATE atp SET Born_Country = "Netherlands" WHERE LTRIM(RTRIM(Born_Country)) = "Hoorn";


UPDATE atp SET Born_Country = "Czech Republic" WHERE Born_Country LIKE "Hradec Kr%";


UPDATE atp SET Born_Country = "Germany" WHERE LTRIM(RTRIM(Born_Country)) = "Humboldt";
UPDATE atp SET Born_Country = "China" WHERE LTRIM(RTRIM(Born_Country)) = "Hunan";
UPDATE atp SET Born_Country = "India" WHERE LTRIM(RTRIM(Born_Country)) = "Hyderabad";
UPDATE atp SET Born_Country = "Japan" WHERE LTRIM(RTRIM(Born_Country)) = "Hyogo";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Hyougo";


UPDATE atp SET Born_Country = "Finland" WHERE Born_Country LIKE "Hyvink%";


UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Sioux City, IA";
UPDATE atp SET Born_Country = "Romania" WHERE LTRIM(RTRIM(Born_Country)) = "Iasi";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Boise, Idaho";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Chicago, IL";


UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) LIKE "%Illinois%";


UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Indianapolis, IN";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Indianapolis";
UPDATE atp SET Born_Country = "Chile" WHERE LTRIM(RTRIM(Born_Country)) = "Iquique";
UPDATE atp SET Born_Country = "Iran, Islamic Republic of" WHERE LTRIM(RTRIM(Born_Country)) = "Arak, Iran";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Irvine";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Irvington";
UPDATE atp SET Born_Country = "Japan" WHERE LTRIM(RTRIM(Born_Country)) = "Ishikawa";
UPDATE atp SET Born_Country = "Turkey" WHERE LTRIM(RTRIM(Born_Country)) = "Istanbul";
UPDATE atp SET Born_Country = "Germany" WHERE LTRIM(RTRIM(Born_Country)) = "Itzehoe";
UPDATE atp SET Born_Country = "Côte d'Ivoire" WHERE LTRIM(RTRIM(Born_Country)) = "Adzope, Ivory Coast";
UPDATE atp SET Born_Country = "Turkey" WHERE LTRIM(RTRIM(Born_Country)) = "Izmir";
UPDATE atp SET Born_Country = "Korea, Republic of" WHERE LTRIM(RTRIM(Born_Country)) = "Jeju";
UPDATE atp SET Born_Country = "Spain" WHERE LTRIM(RTRIM(Born_Country)) = "Jerez de la frontera";
UPDATE atp SET Born_Country = "China" WHERE LTRIM(RTRIM(Born_Country)) = "Jiangsu";
UPDATE atp SET Born_Country = "South Africa" WHERE LTRIM(RTRIM(Born_Country)) = "Johanesburg";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Kalamazoo";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "kanagawa";
UPDATE atp SET Born_Country = "Sweden" WHERE LTRIM(RTRIM(Born_Country)) = "Karlskrona";
UPDATE atp SET Born_Country = "Russian Federation" WHERE LTRIM(RTRIM(Born_Country)) = "Kazan";
UPDATE atp SET Born_Country = "Taiwan, Province of China" WHERE LTRIM(RTRIM(Born_Country)) = "keelung";
UPDATE atp SET Born_Country = "Ukraine" WHERE LTRIM(RTRIM(Born_Country)) = "Kharkiv";
UPDATE atp SET Born_Country = "Ukraine" WHERE LTRIM(RTRIM(Born_Country)) = "Kiev";
UPDATE atp SET Born_Country = "United Kingdom" WHERE LTRIM(RTRIM(Born_Country)) = "KINGSTON UPON THAMES";
UPDATE atp SET Born_Country = "Congo, the Democratic Republic of the" WHERE LTRIM(RTRIM(Born_Country)) = "Kinshasa";
UPDATE atp SET Born_Country = "Austria" WHERE LTRIM(RTRIM(Born_Country)) = "Klagenfurt";
UPDATE atp SET Born_Country = "Czech Republic" WHERE LTRIM(RTRIM(Born_Country)) = "Klatovy";
UPDATE atp SET Born_Country = "Czech Republic" WHERE LTRIM(RTRIM(Born_Country)) = "Kolin";
UPDATE atp SET Born_Country = "India" WHERE LTRIM(RTRIM(Born_Country)) = "Kolkata";


UPDATE atp SET Born_Country = "Korea, Republic of" WHERE LTRIM(RTRIM(Born_Country)) LIKE "%Korea%";


UPDATE atp SET Born_Country = "Korea, Republic of" WHERE LTRIM(RTRIM(Born_Country)) = "Seoul, Korea (South)";
UPDATE atp SET Born_Country = "Sweden" WHERE LTRIM(RTRIM(Born_Country)) = "Kristianstad";
UPDATE atp SET Born_Country = "Ukraine" WHERE LTRIM(RTRIM(Born_Country)) = "Krivoy Rog";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Wichita, KS";
UPDATE atp SET Born_Country = "Ukraine" WHERE LTRIM(RTRIM(Born_Country)) = "Kyiv";
UPDATE atp SET Born_Country = "Korea, Republic of" WHERE LTRIM(RTRIM(Born_Country)) = "Kyunggi-do";
UPDATE atp SET Born_Country = "Italy" WHERE LTRIM(RTRIM(Born_Country)) = "L Aquila";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Metairie, LA";
UPDATE atp SET Born_Country = "Bolivia, Plurinational State of" WHERE LTRIM(RTRIM(Born_Country)) = "La Paz";
UPDATE atp SET Born_Country = "Argentina" WHERE LTRIM(RTRIM(Born_Country)) = "La Plata";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "La Roche-sur-Yon";
UPDATE atp SET Born_Country = "Spain" WHERE LTRIM(RTRIM(Born_Country)) = "Las Palmas";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "Le Pont-De-Beauvoisin";
UPDATE atp SET Born_Country = "United Kingdom" WHERE LTRIM(RTRIM(Born_Country)) = "Leeds";
UPDATE atp SET Born_Country = "Netherlands" WHERE LTRIM(RTRIM(Born_Country)) = "Lelystad";
UPDATE atp SET Born_Country = "Spain" WHERE LTRIM(RTRIM(Born_Country)) = "Leon";
UPDATE atp SET Born_Country = "Belgium" WHERE LTRIM(RTRIM(Born_Country)) = "leuven";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "Levallois";
UPDATE atp SET Born_Country = "Italy" WHERE LTRIM(RTRIM(Born_Country)) = "Licata";
UPDATE atp SET Born_Country = "Peru" WHERE LTRIM(RTRIM(Born_Country)) = "Lima";
UPDATE atp SET Born_Country = "Austria" WHERE LTRIM(RTRIM(Born_Country)) = "Linz";
UPDATE atp SET Born_Country = "Portugal" WHERE LTRIM(RTRIM(Born_Country)) = "Lisboa";
UPDATE atp SET Born_Country = "Portugal" WHERE LTRIM(RTRIM(Born_Country)) = "Lisbon";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Lithonia GA";


UPDATE atp SET Born_Country = "Belgium" WHERE (Born_Country LIKE "Li%" AND Born_Country LIKE "%ge");


UPDATE atp SET Born_Country = "Poland" WHERE LTRIM(RTRIM(Born_Country)) = "Lodz";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Loma linda";
UPDATE atp SET Born_Country = "United Kingdom" WHERE LTRIM(RTRIM(Born_Country)) = "London";


UPDATE atp SET Born_Country = "Brazil" WHERE Born_Country LIKE "%Londrina- Paran%";


UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "Longjumeau";
UPDATE atp SET Born_Country = "Canada" WHERE LTRIM(RTRIM(Born_Country)) = "Longueuil";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "Lons le saunier";
UPDATE atp SET Born_Country = "Switzerland" WHERE LTRIM(RTRIM(Born_Country)) = "Lugano";
UPDATE atp SET Born_Country = "Sweden" WHERE LTRIM(RTRIM(Born_Country)) = "Lund";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "Lyon";


UPDATE atp SET Born_Country = "Germany" WHERE Born_Country LIKE "%beck%";


UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Springfield, MA";
UPDATE atp SET Born_Country = "Macedonia, the Former Yugoslav Republic of" WHERE LTRIM(RTRIM(Born_Country)) = "Skopje, Macedonia";
UPDATE atp SET Born_Country = "Italy" WHERE LTRIM(RTRIM(Born_Country)) = "Macerata";
UPDATE atp SET Born_Country = "Spain" WHERE LTRIM(RTRIM(Born_Country)) = "Madrid";
UPDATE atp SET Born_Country = "Argentina" WHERE LTRIM(RTRIM(Born_Country)) = "Mar del Palta";
UPDATE atp SET Born_Country = "Argentina" WHERE LTRIM(RTRIM(Born_Country)) = "Marco Juarez";
UPDATE atp SET Born_Country = "Slovenia" WHERE LTRIM(RTRIM(Born_Country)) = "maribor";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "Marseille";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "Martigues";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Baltimore, Maryland";
UPDATE atp SET Born_Country = "Brazil" WHERE LTRIM(RTRIM(Born_Country)) = "Sinop, Mato Grosso";
UPDATE atp SET Born_Country = "Australia" WHERE LTRIM(RTRIM(Born_Country)) = "Melbourne";
UPDATE atp SET Born_Country = "Argentina" WHERE LTRIM(RTRIM(Born_Country)) = "Mendoza";
UPDATE atp SET Born_Country = "Argentina" WHERE LTRIM(RTRIM(Born_Country)) = "Merlo";
UPDATE atp SET Born_Country = "Italy" WHERE LTRIM(RTRIM(Born_Country)) = "Messina";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Grayling, MI";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Miami";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Detroit, Michigan";
UPDATE atp SET Born_Country = "Italy" WHERE LTRIM(RTRIM(Born_Country)) = "Milano";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Mineola";
UPDATE atp SET Born_Country = "Belarus" WHERE LTRIM(RTRIM(Born_Country)) = "Minsk";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Minneapolis, MN";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "St. Louis, MO";
UPDATE atp SET Born_Country = "Moldova, Republic of" WHERE LTRIM(RTRIM(Born_Country)) = "Chisinau, Moldova";
UPDATE atp SET Born_Country = "Italy" WHERE LTRIM(RTRIM(Born_Country)) = "Monselice";
UPDATE atp SET Born_Country = "Italy" WHERE LTRIM(RTRIM(Born_Country)) = "Monterotondo";
UPDATE atp SET Born_Country = "Portugal" WHERE LTRIM(RTRIM(Born_Country)) = "Montijo";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "Monto";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "Montpellier";
UPDATE atp SET Born_Country = "Canada" WHERE LTRIM(RTRIM(Born_Country)) = "Montreal";
UPDATE atp SET Born_Country = "Czech Republic" WHERE LTRIM(RTRIM(Born_Country)) = "Moravska Trebova";
UPDATE atp SET Born_Country = "Russian Federation" WHERE LTRIM(RTRIM(Born_Country)) = "Moscow";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Hattiesburg, MS";
UPDATE atp SET Born_Country = "Germany" WHERE LTRIM(RTRIM(Born_Country)) = "Muenster";
UPDATE atp SET Born_Country = "India" WHERE LTRIM(RTRIM(Born_Country)) = "Mumbai";
UPDATE atp SET Born_Country = "Germany" WHERE LTRIM(RTRIM(Born_Country)) = "Munich";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Murrieta";
UPDATE atp SET Born_Country = "India" WHERE LTRIM(RTRIM(Born_Country)) = "Mysore";


UPDATE atp SET Born_Country = "Germany" WHERE Born_Country LIKE "%nchengladbach";


UPDATE atp SET Born_Country = "Japan" WHERE LTRIM(RTRIM(Born_Country)) = "Nagoya";
UPDATE atp SET Born_Country = "Uzbekistan" WHERE LTRIM(RTRIM(Born_Country)) = "Namangan";
UPDATE atp SET Born_Country = "Belgium" WHERE LTRIM(RTRIM(Born_Country)) = "Namur";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Wilmington, NC";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "Neuilly-sur-Seine";
UPDATE atp SET Born_Country = "New Zealand" WHERE LTRIM(RTRIM(Born_Country)) = "New Plymouth";
UPDATE atp SET Born_Country = "Taiwan, Province of China" WHERE LTRIM(RTRIM(Born_Country)) = "New Taipei City";


UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) LIKE "%New York%";


UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "New York City";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "New York New York";
UPDATE atp SET Born_Country = "United Kingdom" WHERE LTRIM(RTRIM(Born_Country)) = "Newcastle upon Tyne";
UPDATE atp SET Born_Country = "Canada" WHERE LTRIM(RTRIM(Born_Country)) = "Newmarket";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Newport";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "NIMES";
UPDATE atp SET Born_Country = "Japan" WHERE LTRIM(RTRIM(Born_Country)) = "nishinomiya";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Hoboken, NJ";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "Nogent sur marne";
UPDATE atp SET Born_Country = "United Kingdom" WHERE LTRIM(RTRIM(Born_Country)) = "Norwich, Norfolk";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Brevard, North Carolina";
UPDATE atp SET Born_Country = "Russian Federation" WHERE LTRIM(RTRIM(Born_Country)) = "Vladikavkaz, North-Ossetia";
UPDATE atp SET Born_Country = "United Kingdom" WHERE LTRIM(RTRIM(Born_Country)) = "Norwich";
UPDATE atp SET Born_Country = "United Kingdom" WHERE LTRIM(RTRIM(Born_Country)) = "Nottingham";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "Noumea";


UPDATE atp SET Born_Country = "France" WHERE Born_Country LIKE "Noum%";

UPDATE atp SET Born_Country = "Italy" WHERE LTRIM(RTRIM(Born_Country)) = "Novara";
UPDATE atp SET Born_Country = "Serbia" WHERE LTRIM(RTRIM(Born_Country)) = "Novi Sad";
UPDATE atp SET Born_Country = "Russian Federation" WHERE LTRIM(RTRIM(Born_Country)) = "novosibirsk";
UPDATE atp SET Born_Country = "Uzbekistan" WHERE LTRIM(RTRIM(Born_Country)) = "Nukus";
UPDATE atp SET Born_Country = "Germany" WHERE LTRIM(RTRIM(Born_Country)) = "Nuremberg";
UPDATE atp SET Born_Country = "Germany" WHERE LTRIM(RTRIM(Born_Country)) = "Nurtingen";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Merrick, NY";
UPDATE atp SET Born_Country = "Canada" WHERE LTRIM(RTRIM(Born_Country)) = "Oakville";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Medina, OH";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Massilon, Ohio";
UPDATE atp SET Born_Country = "Japan" WHERE LTRIM(RTRIM(Born_Country)) = "Okayama";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Olathe";


UPDATE atp SET Born_Country = "Portugal" WHERE Born_Country LIKE "Oliveira de Azem%";


UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Olney";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Omaha";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "The Dalles, OR";
UPDATE atp SET Born_Country = "Algeria" WHERE LTRIM(RTRIM(Born_Country)) = "oran";
UPDATE atp SET Born_Country = "Russian Federation" WHERE LTRIM(RTRIM(Born_Country)) = "Orenbourg";


UPDATE atp SET Born_Country = "Japan" WHERE LTRIM(RTRIM(Born_Country)) LIKE "%Osaka%";


UPDATE atp SET Born_Country = "Japan" WHERE LTRIM(RTRIM(Born_Country)) = "Osaka Japan";
UPDATE atp SET Born_Country = "Czech Republic" WHERE LTRIM(RTRIM(Born_Country)) = "Ostrava";
UPDATE atp SET Born_Country = "Czech Republic" WHERE LTRIM(RTRIM(Born_Country)) = "Ostrov";
UPDATE atp SET Born_Country = "Poland" WHERE LTRIM(RTRIM(Born_Country)) = "Ostrow Wlkp";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Pittsburgh, PA";



UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) LIKE "%U.S.A.%";


UPDATE atp SET Born_Country = "Germany" WHERE LTRIM(RTRIM(Born_Country)) = "Paderborn";
UPDATE atp SET Born_Country = "Spain" WHERE LTRIM(RTRIM(Born_Country)) = "Palma de Mallorca";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Palo Alto";
UPDATE atp SET Born_Country = "Spain" WHERE LTRIM(RTRIM(Born_Country)) = "Pamplona";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "Paris";


UPDATE atp SET Born_Country = "Uruguay" WHERE Born_Country LIKE "Paysand%";


UPDATE atp SET Born_Country = "Portugal" WHERE LTRIM(RTRIM(Born_Country)) = "Peniche";
UPDATE atp SET Born_Country = "Australia" WHERE LTRIM(RTRIM(Born_Country)) = "Penrith";
UPDATE atp SET Born_Country = "Russian Federation" WHERE LTRIM(RTRIM(Born_Country)) = "Penza";
UPDATE atp SET Born_Country = "Colombia" WHERE LTRIM(RTRIM(Born_Country)) = "Pereira";
UPDATE atp SET Born_Country = "Brazil" WHERE LTRIM(RTRIM(Born_Country)) = "Recife, Pernambuco";
UPDATE atp SET Born_Country = "Australia" WHERE LTRIM(RTRIM(Born_Country)) = "Perth";
UPDATE atp SET Born_Country = "Italy" WHERE LTRIM(RTRIM(Born_Country)) = "Perugia";
UPDATE atp SET Born_Country = "Italy" WHERE LTRIM(RTRIM(Born_Country)) = "Pesaro";
UPDATE atp SET Born_Country = "Italy" WHERE LTRIM(RTRIM(Born_Country)) = "Pescara";
UPDATE atp SET Born_Country = "Israel" WHERE LTRIM(RTRIM(Born_Country)) = "Petach Tikva";
UPDATE atp SET Born_Country = "Brazil" WHERE LTRIM(RTRIM(Born_Country)) = "Pilar";
UPDATE atp SET Born_Country = "Czech Republic" WHERE LTRIM(RTRIM(Born_Country)) = "Pilsen";
UPDATE atp SET Born_Country = "Italy" WHERE LTRIM(RTRIM(Born_Country)) = "Pisa";
UPDATE atp SET Born_Country = "Romania" WHERE LTRIM(RTRIM(Born_Country)) = "Pitesti";
UPDATE atp SET Born_Country = "Romania" WHERE LTRIM(RTRIM(Born_Country)) = "Ploiesti";
UPDATE atp SET Born_Country = "Haiti" WHERE LTRIM(RTRIM(Born_Country)) = "Port au Prince";
UPDATE atp SET Born_Country = "South Africa" WHERE LTRIM(RTRIM(Born_Country)) = "Port Elizabeth";
UPDATE atp SET Born_Country = "Australia" WHERE LTRIM(RTRIM(Born_Country)) = "Port Lincoln";
UPDATE atp SET Born_Country = "Australia" WHERE LTRIM(RTRIM(Born_Country)) = "Port Pirie";
UPDATE atp SET Born_Country = "Portugal" WHERE LTRIM(RTRIM(Born_Country)) = "Porto";
UPDATE atp SET Born_Country = "Brazil" WHERE LTRIM(RTRIM(Born_Country)) = "Porto Alegre";
UPDATE atp SET Born_Country = "Austria" WHERE LTRIM(RTRIM(Born_Country)) = "Portschach am Worthersee";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "Pouillon";
UPDATE atp SET Born_Country = "Czech Republic" WHERE LTRIM(RTRIM(Born_Country)) = "Prague";
UPDATE atp SET Born_Country = "South Africa" WHERE LTRIM(RTRIM(Born_Country)) = "Pretoria";
UPDATE atp SET Born_Country = "Poland" WHERE LTRIM(RTRIM(Born_Country)) = "Priemysl";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Princeton";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Princeton NJ";
UPDATE atp SET Born_Country = "Colombia" WHERE LTRIM(RTRIM(Born_Country)) = "Providencia";
UPDATE atp SET Born_Country = "Dominican Republic" WHERE LTRIM(RTRIM(Born_Country)) = "Puerto Plata";
UPDATE atp SET Born_Country = "India" WHERE LTRIM(RTRIM(Born_Country)) = "Pune";
UPDATE atp SET Born_Country = "Chile" WHERE LTRIM(RTRIM(Born_Country)) = "Punta Arenas";
UPDATE atp SET Born_Country = "Mexico" WHERE LTRIM(RTRIM(Born_Country)) = "Queretaro";
UPDATE atp SET Born_Country = "Ecuador" WHERE LTRIM(RTRIM(Born_Country)) = "Quito";
UPDATE atp SET Born_Country = "Argentina" WHERE LTRIM(RTRIM(Born_Country)) = "Rauch";
UPDATE atp SET Born_Country = "Italy" WHERE LTRIM(RTRIM(Born_Country)) = "Ravenna";
UPDATE atp SET Born_Country = "United Kingdom" WHERE LTRIM(RTRIM(Born_Country)) = "Redditch";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "REIMS";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "Rennes";
UPDATE atp SET Born_Country = "Germany" WHERE LTRIM(RTRIM(Born_Country)) = "Reutlingen";
UPDATE atp SET Born_Country = "Switzerland" WHERE LTRIM(RTRIM(Born_Country)) = "Rheinfelden";
UPDATE atp SET Born_Country = "Italy" WHERE LTRIM(RTRIM(Born_Country)) = "Rimini";
UPDATE atp SET Born_Country = "Romania" WHERE LTRIM(RTRIM(Born_Country)) = "Rm Valcea";
UPDATE atp SET Born_Country = "Belgium" WHERE LTRIM(RTRIM(Born_Country)) = "Roeselare";
UPDATE atp SET Born_Country = "Italy" WHERE LTRIM(RTRIM(Born_Country)) = "Roma";
UPDATE atp SET Born_Country = "Italy" WHERE LTRIM(RTRIM(Born_Country)) = "Rome";
UPDATE atp SET Born_Country = "Russian Federation" WHERE LTRIM(RTRIM(Born_Country)) = "Rostov-on-Don";
UPDATE atp SET Born_Country = "Germany" WHERE LTRIM(RTRIM(Born_Country)) = "Rotenburg";
UPDATE atp SET Born_Country = "Netherlands" WHERE LTRIM(RTRIM(Born_Country)) = "Rotterdam";
UPDATE atp SET Born_Country = "Italy" WHERE LTRIM(RTRIM(Born_Country)) = "Rovato (Brescia)";
UPDATE atp SET Born_Country = "Italy" WHERE LTRIM(RTRIM(Born_Country)) = "Rovereto";
UPDATE atp SET Born_Country = "South Africa" WHERE LTRIM(RTRIM(Born_Country)) = "King William's Town, RSA";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "Rueil-Malmaison";
UPDATE atp SET Born_Country = "Romania" WHERE LTRIM(RTRIM(Born_Country)) = "Klausenburg, Rumania";


UPDATE atp SET Born_Country = "Russian Federation" WHERE LTRIM(RTRIM(Born_Country)) LIKE "%Russia%";


UPDATE atp SET Born_Country = "Australia" WHERE LTRIM(RTRIM(Born_Country)) = "Adelaide, S.A. Australia";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Sacramento";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "Saint Denis Reunion";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "Saint Etienne";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "Saint Jean de Maurienne";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "Saint-julien-en-genevois";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "Saint-Nazaire";
UPDATE atp SET Born_Country = "Russian Federation" WHERE LTRIM(RTRIM(Born_Country)) = "Saint-Petersburg";
UPDATE atp SET Born_Country = "Northern Mariana Islands" WHERE LTRIM(RTRIM(Born_Country)) = "Saipan";
UPDATE atp SET Born_Country = "Japan" WHERE LTRIM(RTRIM(Born_Country)) = "Saitma";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Salem";
UPDATE atp SET Born_Country = "Mexico" WHERE LTRIM(RTRIM(Born_Country)) = "Saltillo";
UPDATE atp SET Born_Country = "Russian Federation" WHERE LTRIM(RTRIM(Born_Country)) = "Samara";
UPDATE atp SET Born_Country = "Indonesia" WHERE LTRIM(RTRIM(Born_Country)) = "Samosir Island";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "San Antonio";
UPDATE atp SET Born_Country = "Italy" WHERE LTRIM(RTRIM(Born_Country)) = "San Benedetto del Tronto";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "San Diego";
UPDATE atp SET Born_Country = "Trinidad and Tobago" WHERE LTRIM(RTRIM(Born_Country)) = "San Fernando";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "San Jose";
UPDATE atp SET Born_Country = "Puerto Rico" WHERE LTRIM(RTRIM(Born_Country)) = "San Juan";
UPDATE atp SET Born_Country = "Spain" WHERE LTRIM(RTRIM(Born_Country)) = "San Sebastian";
UPDATE atp SET Born_Country = "Italy" WHERE LTRIM(RTRIM(Born_Country)) = "Sanremo";
UPDATE atp SET Born_Country = "Spain" WHERE LTRIM(RTRIM(Born_Country)) = "Sant Carles de la Rapita";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Santa Ana";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Santa Cruz";
UPDATE atp SET Born_Country = "Brazil" WHERE LTRIM(RTRIM(Born_Country)) = "Santa Cruz de Bezana";
UPDATE atp SET Born_Country = "Brazil" WHERE LTRIM(RTRIM(Born_Country)) = "Santa Cruz do Sul";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Santa Fe";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Santa Monica";
UPDATE atp SET Born_Country = "Chile" WHERE LTRIM(RTRIM(Born_Country)) = "Santiago";
UPDATE atp SET Born_Country = "Dominican Republic" WHERE LTRIM(RTRIM(Born_Country)) = "Santiago De Los Caballeros";
UPDATE atp SET Born_Country = "Dominican Republic" WHERE LTRIM(RTRIM(Born_Country)) = "Santo Domingo";
UPDATE atp SET Born_Country = "Brazil" WHERE LTRIM(RTRIM(Born_Country)) = "Sao paulo";
UPDATE atp SET Born_Country = "Bosnia and Herzegovina" WHERE LTRIM(RTRIM(Born_Country)) = "Sarajevo";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Columbia, SC";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "Schoelcher";
UPDATE atp SET Born_Country = "Germany" WHERE LTRIM(RTRIM(Born_Country)) = "schwaebisch hall";
UPDATE atp SET Born_Country = "Austria" WHERE LTRIM(RTRIM(Born_Country)) = "Schwaz";


UPDATE atp SET Born_Country = "United Kingdom" WHERE LTRIM(RTRIM(Born_Country)) LIKE "%Scotland%";


UPDATE atp SET Born_Country = "Korea, Republic of" WHERE LTRIM(RTRIM(Born_Country)) = "Seoul";
UPDATE atp SET Born_Country = "Brazil" WHERE LTRIM(RTRIM(Born_Country)) = "Sertaozinho";
UPDATE atp SET Born_Country = "China" WHERE LTRIM(RTRIM(Born_Country)) = "Shanghai";
UPDATE atp SET Born_Country = "Japan" WHERE LTRIM(RTRIM(Born_Country)) = "Shizuoka";
UPDATE atp SET Born_Country = "Kazakhstan" WHERE LTRIM(RTRIM(Born_Country)) = "Shymkent";
UPDATE atp SET Born_Country = "Lithuania" WHERE LTRIM(RTRIM(Born_Country)) = "Siauliai";
UPDATE atp SET Born_Country = "China" WHERE LTRIM(RTRIM(Born_Country)) = "sichuan suining";
UPDATE atp SET Born_Country = "Bulgaria" WHERE LTRIM(RTRIM(Born_Country)) = "Sliven";
UPDATE atp SET Born_Country = "Slovakia" WHERE LTRIM(RTRIM(Born_Country)) = "Povazska Bystrica, Slovak";



UPDATE atp SET Born_Country = "Slovakia" WHERE LTRIM(RTRIM(Born_Country)) LIKE "%Slovak Republic%";


UPDATE atp SET Born_Country = "Bulgaria" WHERE LTRIM(RTRIM(Born_Country)) = "Sofia";
UPDATE atp SET Born_Country = "Australia" WHERE LTRIM(RTRIM(Born_Country)) = "Modbury, South Australia";



UPDATE atp SET Born_Country = "Korea, Republic of" WHERE LTRIM(RTRIM(Born_Country)) LIKE "%South Korea%";



UPDATE atp SET Born_Country = "Spain" WHERE LTRIM(RTRIM(Born_Country)) = "Sant Carters de la Rapita,Spai";
UPDATE atp SET Born_Country = "Croatia" WHERE LTRIM(RTRIM(Born_Country)) = "Split";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Spokane";
UPDATE atp SET Born_Country = "United Kingdom" WHERE LTRIM(RTRIM(Born_Country)) = "St Albans";
UPDATE atp SET Born_Country = "Australia" WHERE LTRIM(RTRIM(Born_Country)) = "St Kilda East";
UPDATE atp SET Born_Country = "Canada" WHERE LTRIM(RTRIM(Born_Country)) = "St. John's";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Stamford";
UPDATE atp SET Born_Country = "Germany" WHERE LTRIM(RTRIM(Born_Country)) = "Starnberg";
UPDATE atp SET Born_Country = "United Kingdom" WHERE LTRIM(RTRIM(Born_Country)) = "Stevenage";
UPDATE atp SET Born_Country = "Sweden" WHERE LTRIM(RTRIM(Born_Country)) = "Stockholm";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "Strasbourg";
UPDATE atp SET Born_Country = "Italy" WHERE LTRIM(RTRIM(Born_Country)) = "Subiaco";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "Sucy En Brie";
UPDATE atp SET Born_Country = "United Kingdom" WHERE LTRIM(RTRIM(Born_Country)) = "Sunderland";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "Suresnes";
UPDATE atp SET Born_Country = "Korea, Republic of" WHERE LTRIM(RTRIM(Born_Country)) = "Suwon";
UPDATE atp SET Born_Country = "Australia" WHERE LTRIM(RTRIM(Born_Country)) = "Sydney";




UPDATE atp SET Born_Country = "Brazil" WHERE Born_Country LIKE  "%o Bernardo do Campo";
UPDATE atp SET Born_Country = "Brazil" WHERE Born_Country LIKE  "%o Paulo";
UPDATE atp SET Born_Country = "France" WHERE Born_Country LIKE  "%vres";



UPDATE atp SET Born_Country = "Russian Federation" WHERE LTRIM(RTRIM(Born_Country)) = "Taganrog";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "Tahiti";
UPDATE atp SET Born_Country = "Taiwan, Province of China" WHERE LTRIM(RTRIM(Born_Country)) = "Tainan";



UPDATE atp SET Born_Country = "Taiwan, Province of China" WHERE LTRIM(RTRIM(Born_Country)) LIKE "%Taipei%";


UPDATE atp SET Born_Country = "Taiwan, Province of China" WHERE LTRIM(RTRIM(Born_Country)) = "Taipei City";


UPDATE atp SET Born_Country = "Taiwan, Province of China" WHERE LTRIM(RTRIM(Born_Country)) LIKE "%Taiwan%";


UPDATE atp SET Born_Country = "Estonia" WHERE LTRIM(RTRIM(Born_Country)) = "Tallinn";
UPDATE atp SET Born_Country = "Mexico" WHERE LTRIM(RTRIM(Born_Country)) = "Tampico";
UPDATE atp SET Born_Country = "Estonia" WHERE LTRIM(RTRIM(Born_Country)) = "Tartu";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Tarzana";
UPDATE atp SET Born_Country = "Uzbekistan" WHERE LTRIM(RTRIM(Born_Country)) = "Tashkent";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Taunton";
UPDATE atp SET Born_Country = "Turkey" WHERE LTRIM(RTRIM(Born_Country)) = "Tekirdag";
UPDATE atp SET Born_Country = "Kazakhstan" WHERE LTRIM(RTRIM(Born_Country)) = "Temirtau";


UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) LIKE "%Tennessee";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) LIKE "%Texas%";
UPDATE atp SET Born_Country = "Netherlands" WHERE LTRIM(RTRIM(Born_Country)) LIKE "%The Netherlands%";



UPDATE atp SET Born_Country = "China" WHERE LTRIM(RTRIM(Born_Country)) = "Tianjin";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Memphis, TN";
UPDATE atp SET Born_Country = "Madagascar" WHERE LTRIM(RTRIM(Born_Country)) = "Toamasina";


UPDATE atp SET Born_Country = "Japan" WHERE LTRIM(RTRIM(Born_Country)) LIKE "%Tokyo%";


UPDATE atp SET Born_Country = "Poland" WHERE LTRIM(RTRIM(Born_Country)) = "Tomaszow Mazowiecki";
UPDATE atp SET Born_Country = "Russian Federation" WHERE LTRIM(RTRIM(Born_Country)) = "Tomsk";
UPDATE atp SET Born_Country = "Italy" WHERE LTRIM(RTRIM(Born_Country)) = "torino";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "Toulon";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "Toulouse";
UPDATE atp SET Born_Country = "Japan" WHERE LTRIM(RTRIM(Born_Country)) = "Toyama";
UPDATE atp SET Born_Country = "Australia" WHERE LTRIM(RTRIM(Born_Country)) = "Traralgon";
UPDATE atp SET Born_Country = "Germany" WHERE LTRIM(RTRIM(Born_Country)) = "Traunstein";
UPDATE atp SET Born_Country = "Slovenia" WHERE LTRIM(RTRIM(Born_Country)) = "Trbovlje";
UPDATE atp SET Born_Country = "Italy" WHERE LTRIM(RTRIM(Born_Country)) = "Trieste";
UPDATE atp SET Born_Country = "Trinidad and Tobago" WHERE LTRIM(RTRIM(Born_Country)) = "Trinidad";
UPDATE atp SET Born_Country = "Slovakia" WHERE LTRIM(RTRIM(Born_Country)) = "Trnava";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Tulsa";
UPDATE atp SET Born_Country = "Italy" WHERE LTRIM(RTRIM(Born_Country)) = "Turin";
UPDATE atp SET Born_Country = "Finland" WHERE LTRIM(RTRIM(Born_Country)) = "Turku";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Arlington, TX";


UPDATE atp SET Born_Country = "Germany" WHERE Born_Country LIKE "%bingen";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) LIKE "%U.S.A%";



UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Columbus, Ohio, U.S.A.";
UPDATE atp SET Born_Country = "Russian Federation" WHERE LTRIM(RTRIM(Born_Country)) = "Ufa";
UPDATE atp SET Born_Country = "Italy" WHERE LTRIM(RTRIM(Born_Country)) = "Urbino";
UPDATE atp SET Born_Country = "Brazil" WHERE LTRIM(RTRIM(Born_Country)) = "Uruguaiana";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Bloomfield Hills, MI, US";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Rancho Santa Fe, CA, USA";
UPDATE atp SET Born_Country = "Netherlands" WHERE LTRIM(RTRIM(Born_Country)) = "Utrecht";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Annandale, VA";
UPDATE atp SET Born_Country = "Czech Republic" WHERE LTRIM(RTRIM(Born_Country)) = "Valasske Mezirici";
UPDATE atp SET Born_Country = "Spain" WHERE LTRIM(RTRIM(Born_Country)) = "Valencia";
UPDATE atp SET Born_Country = "Canada" WHERE LTRIM(RTRIM(Born_Country)) = "Vancouver";
UPDATE atp SET Born_Country = "Bulgaria" WHERE LTRIM(RTRIM(Born_Country)) = "VARNA";



UPDATE atp SET Born_Country = "Venezuela, Bolivarian Republic of" WHERE LTRIM(RTRIM(Born_Country)) LIKE "%Venezuela%";



UPDATE atp SET Born_Country = "Italy" WHERE LTRIM(RTRIM(Born_Country)) = "Vercelli";
UPDATE atp SET Born_Country = "Italy" WHERE LTRIM(RTRIM(Born_Country)) = "Verona";
UPDATE atp SET Born_Country = "Belgium" WHERE LTRIM(RTRIM(Born_Country)) = "Verviers";
UPDATE atp SET Born_Country = "Italy" WHERE LTRIM(RTRIM(Born_Country)) = "vicenza";



UPDATE atp SET Born_Country = "Australia" WHERE LTRIM(RTRIM(Born_Country)) LIKE "%Victoria%";


UPDATE atp SET Born_Country = "Austria" WHERE LTRIM(RTRIM(Born_Country)) = "Vienna";



UPDATE atp SET Born_Country = "Viet Nam" WHERE LTRIM(RTRIM(Born_Country)) LIKE "%Vietnam%";



UPDATE atp SET Born_Country = "Argentina" WHERE LTRIM(RTRIM(Born_Country)) = "Villa Gesell";
UPDATE atp SET Born_Country = "Spain" WHERE LTRIM(RTRIM(Born_Country)) = "Villa Maria Cordoba";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "Villeneuve saint Georges";
UPDATE atp SET Born_Country = "France" WHERE LTRIM(RTRIM(Born_Country)) = "Villeurbanne";
UPDATE atp SET Born_Country = "Lithuania" WHERE LTRIM(RTRIM(Born_Country)) = "Vilnius";
UPDATE atp SET Born_Country = "Belgium" WHERE LTRIM(RTRIM(Born_Country)) = "Vilvoorde";
UPDATE atp SET Born_Country = "India" WHERE LTRIM(RTRIM(Born_Country)) = "Visakhapatnam";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Seattle, WA";
UPDATE atp SET Born_Country = "Netherlands" WHERE LTRIM(RTRIM(Born_Country)) = "Waalwijk";
UPDATE atp SET Born_Country = "Czech Republic" WHERE LTRIM(RTRIM(Born_Country)) = "Walbrzych";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Walnut Creek";
UPDATE atp SET Born_Country = "Poland" WHERE LTRIM(RTRIM(Born_Country)) = "Warsaw";
UPDATE atp SET Born_Country = "Poland" WHERE LTRIM(RTRIM(Born_Country)) = "Warszawa";
UPDATE atp SET Born_Country = "Germany" WHERE LTRIM(RTRIM(Born_Country)) = "Wasserburg am Inn";
UPDATE atp SET Born_Country = "Germany" WHERE LTRIM(RTRIM(Born_Country)) = "Weiden in der Oberpfalz";
UPDATE atp SET Born_Country = "New Zealand" WHERE LTRIM(RTRIM(Born_Country)) = "Wellington";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "West Palm Beach";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Hartland, WI";
UPDATE atp SET Born_Country = "Germany" WHERE LTRIM(RTRIM(Born_Country)) = "Wiesbaden";
UPDATE atp SET Born_Country = "Switzerland" WHERE LTRIM(RTRIM(Born_Country)) = "Wil";
UPDATE atp SET Born_Country = "Netherlands" WHERE LTRIM(RTRIM(Born_Country)) = "Willemstad";
UPDATE atp SET Born_Country = "Namibia" WHERE LTRIM(RTRIM(Born_Country)) = "Windhoek";
UPDATE atp SET Born_Country = "United States" WHERE LTRIM(RTRIM(Born_Country)) = "Winston Salem";
UPDATE atp SET Born_Country = "Belgium" WHERE LTRIM(RTRIM(Born_Country)) = "Woluwe St Lambert";
UPDATE atp SET Born_Country = "Austria" WHERE LTRIM(RTRIM(Born_Country)) = "Wr.Neustadt";
UPDATE atp SET Born_Country = "Poland" WHERE LTRIM(RTRIM(Born_Country)) = "Wroclaw";
UPDATE atp SET Born_Country = "China" WHERE LTRIM(RTRIM(Born_Country)) = "Wuhan";
UPDATE atp SET Born_Country = "China" WHERE LTRIM(RTRIM(Born_Country)) = "Xin jiang";
UPDATE atp SET Born_Country = "Japan" WHERE LTRIM(RTRIM(Born_Country)) = "Yamagata";
UPDATE atp SET Born_Country = "Armenia" WHERE LTRIM(RTRIM(Born_Country)) = "Yerevan";
UPDATE atp SET Born_Country = "Japan" WHERE LTRIM(RTRIM(Born_Country)) = "YOKOHAMA";



UPDATE atp SET Born_Country = "Serbia" WHERE LTRIM(RTRIM(Born_Country)) LIKE  "%Yugoslavia%";


UPDATE atp SET Born_Country = "Croatia" WHERE LTRIM(RTRIM(Born_Country)) = "Zagreb";
UPDATE atp SET Born_Country = "Poland" WHERE LTRIM(RTRIM(Born_Country)) = "Zielona Gora";


UPDATE atp SET Born_Country = "Germany" WHERE Born_Country LIKE "%stringen";

UPDATE atp SET Hand = "Right-Handed, Two-Handed Backhand" WHERE LinkPlayer = "https://www.atptour.com/en/players/arthur-fery/f0dm/player-activity?year=all&matchType=Singles";
UPDATE atp SET Hand = "Ambidextrous, Two-Handed Backhand" WHERE LinkPlayer = "https://www.atptour.com/en/players/marcin-gawron/g978/player-activity?year=all&matchType=Singles";
UPDATE atp SET Hand = "Ambidextrous, Two-Handed Backhand" WHERE LinkPlayer = "https://www.atptour.com/en/players/roberto-arguello/a030/player-activity?year=all&matchType=Singles";


UPDATE atp SET atp.Heigth = 175 WHERE atp.Heigth = 510;
UPDATE atp SET atp.Heigth = 0 WHERE Length(Heigth) < 3;

########################################################################################################

UPDATE atp SET atp.Tournament_Name = "Australian Open" WHERE Tournament_Name = "Australian Open-1";
UPDATE atp SET atp.Tournament_Name = "Australian Open" WHERE Tournament_Name = "Australian Open-2";

UPDATE atp SET Tournament_Country = "Netherlands" WHERE LTRIM(RTRIM(Tournament_Country)) = "'s-Hertogenbosch";
UPDATE atp SET Tournament_Country = "Côte d'Ivoire" WHERE LTRIM(RTRIM(Tournament_Country)) = "Abidjan";
UPDATE atp SET Tournament_Country = "Canada" WHERE LTRIM(RTRIM(Tournament_Country)) = "Calgary, Alberta";
UPDATE atp SET Tournament_Country = "Belgium" WHERE LTRIM(RTRIM(Tournament_Country)) = "Angleur - Liege";
UPDATE atp SET Tournament_Country = "Turkey" WHERE LTRIM(RTRIM(Tournament_Country)) = "Antalya, Antalya";
UPDATE atp SET Tournament_Country = "United States" WHERE LTRIM(RTRIM(Tournament_Country)) = "Fayetteville, Fayetteville, AR";
UPDATE atp SET Tournament_Country = "Argentina" WHERE LTRIM(RTRIM(Tournament_Country)) = "Cordoba, ARG";
UPDATE atp SET Tournament_Country = "Argentina" WHERE LTRIM(RTRIM(Tournament_Country)) = "Buenos Aires, Arg.";
UPDATE atp SET Tournament_Country = "Argentina" WHERE LTRIM(RTRIM(Tournament_Country)) = "Buenos Aires, Argent";
UPDATE atp SET Tournament_Country = "Austria" WHERE LTRIM(RTRIM(Tournament_Country)) = "St Anton-Tirol, Aut.";
UPDATE atp SET Tournament_Country = "Brazil" WHERE LTRIM(RTRIM(Tournament_Country)) = "Bahia";
UPDATE atp SET Tournament_Country = "Spain" WHERE LTRIM(RTRIM(Tournament_Country)) = "Bakio, Bakio";
UPDATE atp SET Tournament_Country = "Thailand" WHERE LTRIM(RTRIM(Tournament_Country)) = "Bangkok";
UPDATE atp SET Tournament_Country = "Spain" WHERE LTRIM(RTRIM(Tournament_Country)) = "Barcelona";


UPDATE atp SET Tournament_Country = "Serbia" WHERE LTRIM(RTRIM(Tournament_Country)) LIKE "%Belgrade%";


UPDATE atp SET Tournament_Country = NULL WHERE Tournament_Country = "Bolivia/Chile";


UPDATE atp SET Tournament_Country = "Bolivia, Plurinational State of" WHERE LTRIM(RTRIM(Tournament_Country)) LIKE "%Bolivia%";
UPDATE atp SET Tournament_Country = "Bosnia and Herzegovina" WHERE LTRIM(RTRIM(Tournament_Country)) LIKE "%Bosnia%";
UPDATE atp SET Tournament_Country = "Bosnia and Herzegovina" WHERE LTRIM(RTRIM(Tournament_Country)) LIKE "%Herzegovina%";


UPDATE atp SET Tournament_Country = "Botswana" WHERE LTRIM(RTRIM(Tournament_Country)) = "Botwana";
UPDATE atp SET Tournament_Country = "France" WHERE LTRIM(RTRIM(Tournament_Country)) = "Bourg-en-Bresse, Bourg-en-Bresse";
UPDATE atp SET Tournament_Country = "Brazil" WHERE LTRIM(RTRIM(Tournament_Country)) = "Florianopolis, BRA";
UPDATE atp SET Tournament_Country = "Brazil" WHERE LTRIM(RTRIM(Tournament_Country)) = "Brasilia";
UPDATE atp SET Tournament_Country = "Slovakia" WHERE LTRIM(RTRIM(Tournament_Country)) = "Bratislava";
UPDATE atp SET Tournament_Country = "Germany" WHERE LTRIM(RTRIM(Tournament_Country)) = "Braunschweig";
UPDATE atp SET Tournament_Country = "Brazil" WHERE LTRIM(RTRIM(Tournament_Country)) = "Santa Caterina, Braz";
UPDATE atp SET Tournament_Country = "Brazil" WHERE LTRIM(RTRIM(Tournament_Country)) = "Brazi";
UPDATE atp SET Tournament_Country = "United Kingdom" WHERE LTRIM(RTRIM(Tournament_Country)) = "Birmingham, Britain";



UPDATE atp SET Tournament_Country = "Brunei Darussalam" WHERE LTRIM(RTRIM(Tournament_Country)) LIKE "%Brunei%";


UPDATE atp SET Tournament_Country = "Romania" WHERE LTRIM(RTRIM(Tournament_Country)) = "Bucharest";
UPDATE atp SET Tournament_Country = "Argentina" WHERE LTRIM(RTRIM(Tournament_Country)) = "Buenos Aires";
UPDATE atp SET Tournament_Country = "Canada" WHERE LTRIM(RTRIM(Tournament_Country)) = "Calgary";


UPDATE atp SET Tournament_Country = "Canada" WHERE LTRIM(RTRIM(Tournament_Country)) LIKE "%Canda";


UPDATE atp SET Tournament_Country = "Puerto Rico" WHERE LTRIM(RTRIM(Tournament_Country)) = "Caribbean";
UPDATE atp SET Tournament_Country = "Morocco" WHERE LTRIM(RTRIM(Tournament_Country)) = "Casablanca";
UPDATE atp SET Tournament_Country = "Taiwan, Province of China" WHERE LTRIM(RTRIM(Tournament_Country)) = "Tao Yuan, Chinese Ta";
UPDATE atp SET Tournament_Country = "Taiwan, Province of China" WHERE LTRIM(RTRIM(Tournament_Country)) = "Taipei, Chinese Taip";


UPDATE atp SET Tournament_Country = "Taiwan, Province of China" WHERE LTRIM(RTRIM(Tournament_Country)) LIKE "%Chinese Taipei%";


UPDATE atp SET Tournament_Country = "Cuba" WHERE LTRIM(RTRIM(Tournament_Country)) = "Ciudad de Habana";
UPDATE atp SET Tournament_Country = "Côte d'Ivoire" WHERE LTRIM(RTRIM(Tournament_Country)) = "Abidjan, CIV";


UPDATE atp SET Tournament_Country = "Colombia" WHERE LTRIM(RTRIM(Tournament_Country)) LIKE "%Col";

UPDATE atp SET Tournament_Country = "Colombia" WHERE LTRIM(RTRIM(Tournament_Country)) = "Bogota, Columbia";
UPDATE atp SET Tournament_Country = "Romania" WHERE LTRIM(RTRIM(Tournament_Country)) = "Constanta";


UPDATE atp SET Tournament_Country = "Croatia" WHERE LTRIM(RTRIM(Tournament_Country)) LIKE "%Crotia";


UPDATE atp SET Tournament_Country = "Czech Republic" WHERE LTRIM(RTRIM(Tournament_Country)) = "Prostejov, CZE";
UPDATE atp SET Tournament_Country = "Czech Republic" WHERE LTRIM(RTRIM(Tournament_Country)) = "Ostrava, Czech Rep.";
UPDATE atp SET Tournament_Country = "Czech Republic" WHERE LTRIM(RTRIM(Tournament_Country)) = "Liberec, Czech Repub";
UPDATE atp SET Tournament_Country = "Slovakia" WHERE LTRIM(RTRIM(Tournament_Country)) LIKE "%Czechoslovakia%";
UPDATE atp SET Tournament_Country = "Dominican Republic" WHERE LTRIM(RTRIM(Tournament_Country)) = "Santo Domingo, D.R.";
UPDATE atp SET Tournament_Country = "United States" WHERE LTRIM(RTRIM(Tournament_Country)) = "Delray Beach";
UPDATE atp SET Tournament_Country = "Denmark" WHERE LTRIM(RTRIM(Tournament_Country)) = "Rungsted Kyst, DEN.";
UPDATE atp SET Tournament_Country = "United Kingdom" WHERE LTRIM(RTRIM(Tournament_Country)) = "Devon";
UPDATE atp SET Tournament_Country = "United Kingdom" WHERE LTRIM(RTRIM(Tournament_Country)) = "Devonport";
UPDATE atp SET Tournament_Country = "Qatar" WHERE LTRIM(RTRIM(Tournament_Country)) LIKE "%Doha%";
UPDATE atp SET Tournament_Country = "Qatar" WHERE LTRIM(RTRIM(Tournament_Country)) = "Domincan Republic";
UPDATE atp SET Tournament_Country = "Ireland" WHERE LTRIM(RTRIM(Tournament_Country)) = "Dublin";
UPDATE atp SET Tournament_Country = "Netherlands" WHERE LTRIM(RTRIM(Tournament_Country)) = "Emmastad, Dutch Anti";
UPDATE atp SET Tournament_Country = "Netherlands" WHERE LTRIM(RTRIM(Tournament_Country)) = "Curacao, Dutch Antil";
UPDATE atp SET Tournament_Country = "Egypt" WHERE LTRIM(RTRIM(Tournament_Country)) = "Cairo, Egpyt";
UPDATE atp SET Tournament_Country = "Netherlands" WHERE LTRIM(RTRIM(Tournament_Country)) = "Elndhoven";
UPDATE atp SET Tournament_Country = "United Kingdom" WHERE LTRIM(RTRIM(Tournament_Country)) LIKE "%England%";
UPDATE atp SET Tournament_Country = "Luxembourg" WHERE LTRIM(RTRIM(Tournament_Country)) = "Esch-sur-Alzette, Esch-sur-Alzette";
UPDATE atp SET Tournament_Country = "Luxembourg" WHERE LTRIM(RTRIM(Tournament_Country)) = "Esch/Alzette";
UPDATE atp SET Tournament_Country = "Portugal" WHERE LTRIM(RTRIM(Tournament_Country)) = "Estoril";
UPDATE atp SET Tournament_Country = "Egypt" WHERE LTRIM(RTRIM(Tournament_Country)) = "Cairo, Eygpt";
UPDATE atp SET Tournament_Country = "Portugal" WHERE LTRIM(RTRIM(Tournament_Country)) = "Faro";
UPDATE atp SET Tournament_Country = "Fiji" WHERE LTRIM(RTRIM(Tournament_Country)) = "Lautoka, Fiji Island";
UPDATE atp SET Tournament_Country = "Brazil" WHERE LTRIM(RTRIM(Tournament_Country)) = "Florianapolis";
UPDATE atp SET Tournament_Country = "France" WHERE LTRIM(RTRIM(Tournament_Country)) = "Forbach, Forbach";
UPDATE atp SET Tournament_Country = "United Kingdom" WHERE LTRIM(RTRIM(Tournament_Country)) = "Birmingham, GBR";
UPDATE atp SET Tournament_Country = "United Kingdom" WHERE LTRIM(RTRIM(Tournament_Country)) LIKE "%Great Britain%";
UPDATE atp SET Tournament_Country = "Guatemala" WHERE LTRIM(RTRIM(Tournament_Country)) = "Guatemala City, GUA";
UPDATE atp SET Tournament_Country = "Brazil" WHERE LTRIM(RTRIM(Tournament_Country)) = "Guarulhos";
UPDATE atp SET Tournament_Country = "Guatemala" WHERE LTRIM(RTRIM(Tournament_Country)) = "Guatemala City";
UPDATE atp SET Tournament_Country = "Ecuador" WHERE LTRIM(RTRIM(Tournament_Country)) = "Guayaquil";
UPDATE atp SET Tournament_Country = "Zimbabwe" WHERE LTRIM(RTRIM(Tournament_Country)) = "Harare";
UPDATE atp SET Tournament_Country = "Israel" WHERE LTRIM(RTRIM(Tournament_Country)) = "Ramat, Hasharon";
UPDATE atp SET Tournament_Country = "Cuba" WHERE LTRIM(RTRIM(Tournament_Country)) = "Havana";
UPDATE atp SET Tournament_Country = "Hong Kong" WHERE LTRIM(RTRIM(Tournament_Country)) LIKE "%HKG%";
UPDATE atp SET Tournament_Country = "Hungary" WHERE LTRIM(RTRIM(Tournament_Country)) = "Hodmezovasarhely, Hu";
UPDATE atp SET Tournament_Country = "Hungary" WHERE LTRIM(RTRIM(Tournament_Country)) = "Szombathely, Hunary";
UPDATE atp SET Tournament_Country = "Indonesia" WHERE LTRIM(RTRIM(Tournament_Country)) = "Jakarta, INA";
UPDATE atp SET Tournament_Country = "Iran, Islamic Republic of" WHERE LTRIM(RTRIM(Tournament_Country)) LIKE "%Iran%";
UPDATE atp SET Tournament_Country = "Israel" WHERE LTRIM(RTRIM(Tournament_Country)) = "Ramat Hasharon, ISR";
UPDATE atp SET Tournament_Country = "Israel" WHERE LTRIM(RTRIM(Tournament_Country)) = "Ramat Hasharon, Isra";
UPDATE atp SET Tournament_Country = "Italy" WHERE LTRIM(RTRIM(Tournament_Country)) = "Torre Del Greco, Ita";
UPDATE atp SET Tournament_Country = "Côte d'Ivoire" WHERE LTRIM(RTRIM(Tournament_Country)) LIKE "%Ivory Coast%";
UPDATE atp SET Tournament_Country = "Indonesia" WHERE LTRIM(RTRIM(Tournament_Country)) = "Jakarta";
UPDATE atp SET Tournament_Country = "Indonesia" WHERE LTRIM(RTRIM(Tournament_Country)) = "Johannesburg";
UPDATE atp SET Tournament_Country = "Taiwan, Province of China" WHERE LTRIM(RTRIM(Tournament_Country)) = "Kaohsiung";
UPDATE atp SET Tournament_Country = "India" WHERE LTRIM(RTRIM(Tournament_Country)) = "Kolkata";
UPDATE atp SET Tournament_Country = "Korea, Republic of" WHERE LTRIM(RTRIM(Tournament_Country)) LIKE "%Korea%";
UPDATE atp SET Tournament_Country = "Russian Federation" WHERE LTRIM(RTRIM(Tournament_Country)) = "Korolev";
UPDATE atp SET Tournament_Country = "Malaysia" WHERE LTRIM(RTRIM(Tournament_Country)) = "Kuala Lampur";
UPDATE atp SET Tournament_Country = "Pakistan" WHERE LTRIM(RTRIM(Tournament_Country)) = "Lahore";
UPDATE atp SET Tournament_Country = "Lao People's Democratic Republic" WHERE LTRIM(RTRIM(Tournament_Country)) = "Laos";
UPDATE atp SET Tournament_Country = "Venezuela, Bolivarian Republic of" WHERE LTRIM(RTRIM(Tournament_Country)) = "Lara";
UPDATE atp SET Tournament_Country = "Martinique" WHERE LTRIM(RTRIM(Tournament_Country)) = "Martinique, Lesser Antilles";
UPDATE atp SET Tournament_Country = "Belgium" WHERE LTRIM(RTRIM(Tournament_Country)) = "Liege";
UPDATE atp SET Tournament_Country = "United Kingdom" WHERE LTRIM(RTRIM(Tournament_Country)) = "London";
UPDATE atp SET Tournament_Country = "Macedonia, the Former Yugoslav Republic of" WHERE LTRIM(RTRIM(Tournament_Country)) = "Skopje, Macedona";
UPDATE atp SET Tournament_Country = "Macedonia, the Former Yugoslav Republic of" WHERE LTRIM(RTRIM(Tournament_Country)) LIKE "%Macedonia%";
UPDATE atp SET Tournament_Country = "Philippines" WHERE LTRIM(RTRIM(Tournament_Country)) = "Manila";
UPDATE atp SET Tournament_Country = "Philippines" WHERE LTRIM(RTRIM(Tournament_Country)) = "Manilla";
UPDATE atp SET Tournament_Country = "Malaysia" WHERE LTRIM(RTRIM(Tournament_Country)) = "Kuala Lumpur, MAS";
UPDATE atp SET Tournament_Country = "Mexico" WHERE LTRIM(RTRIM(Tournament_Country)) = "Coatzacoalcos, Meixco";
UPDATE atp SET Tournament_Country = "Spain" WHERE LTRIM(RTRIM(Tournament_Country)) = "Melilla, Melilla";
UPDATE atp SET Tournament_Country = "Mexico" WHERE LTRIM(RTRIM(Tournament_Country)) = "Mexica";
UPDATE atp SET Tournament_Country = "Mexico" WHERE LTRIM(RTRIM(Tournament_Country)) = "Mexico City";
UPDATE atp SET Tournament_Country = "Belarus" WHERE LTRIM(RTRIM(Tournament_Country)) = "Minsk";
UPDATE atp SET Tournament_Country = "Moldova, Republic of" WHERE LTRIM(RTRIM(Tournament_Country)) = "Chisinau, Moldova";
UPDATE atp SET Tournament_Country = "Moldova, Republic of" WHERE LTRIM(RTRIM(Tournament_Country)) = "Chisinau, Moldovia";
UPDATE atp SET Tournament_Country = "Tunisia" WHERE LTRIM(RTRIM(Tournament_Country)) = "Monastir, Monastir";
UPDATE atp SET Tournament_Country = "Luxembourg" WHERE LTRIM(RTRIM(Tournament_Country)) = "Mondorf-Les-Bains";
UPDATE atp SET Tournament_Country = "Uruguay" WHERE LTRIM(RTRIM(Tournament_Country)) = "Montevideo";
UPDATE atp SET Tournament_Country = "Russian Federation" WHERE LTRIM(RTRIM(Tournament_Country)) = "Moscow";
UPDATE atp SET Tournament_Country = "China" WHERE LTRIM(RTRIM(Tournament_Country)) = "Nanjing";
UPDATE atp SET Tournament_Country = "Netherlands" WHERE LTRIM(RTRIM(Tournament_Country)) = "Rotterdam, NED";
UPDATE atp SET Tournament_Country = "South Africa" WHERE LTRIM(RTRIM(Tournament_Country)) = "Nelspruit";
UPDATE atp SET Tournament_Country = "Switzerland" WHERE LTRIM(RTRIM(Tournament_Country)) = "Neuchatel";
UPDATE atp SET Tournament_Country = "New Caledonia" WHERE LTRIM(RTRIM(Tournament_Country)) = "Noumea, New Caledoni";
UPDATE atp SET Tournament_Country = "New Zealand" WHERE LTRIM(RTRIM(Tournament_Country)) = "Auckland, New Zealan";
UPDATE atp SET Tournament_Country = "Ukraine" WHERE LTRIM(RTRIM(Tournament_Country)) = "Novaya Kakhovka";
UPDATE atp SET Tournament_Country = "Canada" WHERE LTRIM(RTRIM(Tournament_Country)) LIKE "%NZ";
UPDATE atp SET Tournament_Country = "New Zealand" WHERE LTRIM(RTRIM(Tournament_Country)) = "Invercargill, NZL";
UPDATE atp SET Tournament_Country = "United States" WHERE LTRIM(RTRIM(Tournament_Country)) = "Oklahoma City, OK";
UPDATE atp SET Tournament_Country = "Canada" WHERE LTRIM(RTRIM(Tournament_Country)) = "Mississauga, Ontaria";
UPDATE atp SET Tournament_Country = "Australia" WHERE LTRIM(RTRIM(Tournament_Country)) = "Pacific Oceania";
UPDATE atp SET Tournament_Country = "Spain" WHERE LTRIM(RTRIM(Tournament_Country)) = "Palma de Mallorca";
UPDATE atp SET Tournament_Country = "France" WHERE LTRIM(RTRIM(Tournament_Country)) = "Pau";
UPDATE atp SET Tournament_Country = "Philippines" WHERE LTRIM(RTRIM(Tournament_Country)) = "Pasig City, PHI";
UPDATE atp SET Tournament_Country = "Philippines" WHERE LTRIM(RTRIM(Tournament_Country)) = "Phillipines";
UPDATE atp SET Tournament_Country = "South Africa" WHERE LTRIM(RTRIM(Tournament_Country)) = "Polokwane";
UPDATE atp SET Tournament_Country = "Slovenia" WHERE LTRIM(RTRIM(Tournament_Country)) = "Portoroz";
UPDATE atp SET Tournament_Country = "Austria" WHERE LTRIM(RTRIM(Tournament_Country)) = "Portschach";
UPDATE atp SET Tournament_Country = "Slovakia" WHERE LTRIM(RTRIM(Tournament_Country)) = "Presov";
UPDATE atp SET Tournament_Country = "South Africa" WHERE LTRIM(RTRIM(Tournament_Country)) = "Pretoria";
UPDATE atp SET Tournament_Country = "Israel" WHERE LTRIM(RTRIM(Tournament_Country)) = "Ramat Hasharon";
UPDATE atp SET Tournament_Country = "Italy" WHERE LTRIM(RTRIM(Tournament_Country)) = "Reggio Calabria";
UPDATE atp SET Tournament_Country = "France" WHERE LTRIM(RTRIM(Tournament_Country)) = "Reunion Island, Reunion Island";
UPDATE atp SET Tournament_Country = "Brazil" WHERE LTRIM(RTRIM(Tournament_Country)) = "Rio de Janeiro";
UPDATE atp SET Tournament_Country = "Russian Federation" WHERE LTRIM(RTRIM(Tournament_Country)) LIKE "%Russia%";
UPDATE atp SET Tournament_Country = "South Africa" WHERE LTRIM(RTRIM(Tournament_Country)) = "Cape Town, SA";
UPDATE atp SET Tournament_Country = "United States" WHERE LTRIM(RTRIM(Tournament_Country)) = "Salinas";
UPDATE atp SET Tournament_Country = "El Salvador" WHERE LTRIM(RTRIM(Tournament_Country)) = "El Salvador, Salvador";
UPDATE atp SET Tournament_Country = "El Salvador" WHERE LTRIM(RTRIM(Tournament_Country)) = "El Salvador, San Salvador";
UPDATE atp SET Tournament_Country = "Bolivia, Plurinational State of" WHERE LTRIM(RTRIM(Tournament_Country)) = "Santa Cruz de la Sie";
UPDATE atp SET Tournament_Country = "Chile" WHERE LTRIM(RTRIM(Tournament_Country)) = "Chile, Santiago";
UPDATE atp SET Tournament_Country = "Dominican Republic" WHERE LTRIM(RTRIM(Tournament_Country)) = "Santo Domingo";
UPDATE atp SET Tournament_Country = "Italy" WHERE LTRIM(RTRIM(Tournament_Country)) = "Sassari, Sardinia";
UPDATE atp SET Tournament_Country = "Serbia" WHERE LTRIM(RTRIM(Tournament_Country)) = "Belgrade, SCG";
UPDATE atp SET Tournament_Country = "United Kingdom" WHERE LTRIM(RTRIM(Tournament_Country)) LIKE "%Scotland%";
UPDATE atp SET Tournament_Country = "Montenegro" WHERE LTRIM(RTRIM(Tournament_Country)) = "Serbia &amp; Montenegro";
UPDATE atp SET Tournament_Country = "Serbia" WHERE LTRIM(RTRIM(Tournament_Country)) = "Nova Sad, SErgia &amp; M";
UPDATE atp SET Tournament_Country = "Egypt" WHERE LTRIM(RTRIM(Tournament_Country)) = "Sharm El Sheikh";
UPDATE atp SET Tournament_Country = "Slovakia" WHERE LTRIM(RTRIM(Tournament_Country)) LIKE "%Slovak%";
UPDATE atp SET Tournament_Country = "Slovakia" WHERE LTRIM(RTRIM(Tournament_Country)) = "Bratislava, Slovak R";
UPDATE atp SET Tournament_Country = "Slovakia" WHERE LTRIM(RTRIM(Tournament_Country)) = "Slovak Republic";
UPDATE atp SET Tournament_Country = "Slovakia" WHERE LTRIM(RTRIM(Tournament_Country)) = "Kosice, Slovkia";
UPDATE atp SET Tournament_Country = "Slovenia" WHERE LTRIM(RTRIM(Tournament_Country)) = "Portoroz, Solvenia";
UPDATE atp SET Tournament_Country = "South Africa" WHERE LTRIM(RTRIM(Tournament_Country)) = "Doornfontein, South";
UPDATE atp SET Tournament_Country = "South Africa" WHERE LTRIM(RTRIM(Tournament_Country)) = "Durban, South  Africa";
UPDATE atp SET Tournament_Country = "Korea, Republic of" WHERE LTRIM(RTRIM(Tournament_Country)) LIKE "%South Korea%";
UPDATE atp SET Tournament_Country = "Russian Federation" WHERE LTRIM(RTRIM(Tournament_Country)) = "Soviet Union";
UPDATE atp SET Tournament_Country = "Indonesia" WHERE LTRIM(RTRIM(Tournament_Country)) = "Surabaya";
UPDATE atp SET Tournament_Country = "Switzerland" WHERE LTRIM(RTRIM(Tournament_Country)) = "St.Gallen, Switz.";
UPDATE atp SET Tournament_Country = "Syrian Arab Republic" WHERE LTRIM(RTRIM(Tournament_Country)) LIKE "%Syria%";
UPDATE atp SET Tournament_Country = "Taiwan, Province of China" WHERE LTRIM(RTRIM(Tournament_Country)) LIKE "%Taipei%";
UPDATE atp SET Tournament_Country = "Taiwan, Province of China" WHERE LTRIM(RTRIM(Tournament_Country)) LIKE "%Taiwan%";
UPDATE atp SET Tournament_Country = "Uzbekistan" WHERE LTRIM(RTRIM(Tournament_Country)) = "Tashkent";
UPDATE atp SET Tournament_Country = "Australia" WHERE LTRIM(RTRIM(Tournament_Country)) LIKE "%Tasmania";
UPDATE atp SET Tournament_Country = "United Kingdom" WHERE LTRIM(RTRIM(Tournament_Country)) = "TBC";
UPDATE atp SET Tournament_Country = "United States" WHERE LTRIM(RTRIM(Tournament_Country)) = "TBD";
UPDATE atp SET Tournament_Country = "Iran, Islamic Republic of" WHERE LTRIM(RTRIM(Tournament_Country)) = "Tehran";
UPDATE atp SET Tournament_Country = "United States" WHERE LTRIM(RTRIM(Tournament_Country)) = "Houston, Texas";
UPDATE atp SET Tournament_Country = "Thailand" WHERE LTRIM(RTRIM(Tournament_Country)) = "Nonthaburi, THA";
UPDATE atp SET Tournament_Country = "Netherlands" WHERE LTRIM(RTRIM(Tournament_Country)) = "The Hague, The Hague";
UPDATE atp SET Tournament_Country = "Netherlands" WHERE LTRIM(RTRIM(Tournament_Country)) = "Amsterdam, The Nethe";
UPDATE atp SET Tournament_Country = "Netherlands" WHERE LTRIM(RTRIM(Tournament_Country)) LIKE "%The Netherlands%";
UPDATE atp SET Tournament_Country = "Mexico" WHERE LTRIM(RTRIM(Tournament_Country)) = "Toluca";
UPDATE atp SET Tournament_Country = "France" WHERE LTRIM(RTRIM(Tournament_Country)) = "Toulouse";
UPDATE atp SET Tournament_Country = "Taiwan, Province of China" WHERE LTRIM(RTRIM(Tournament_Country)) = "Tai-Chung, TPE";
UPDATE atp SET Tournament_Country = "Trinidad and Tobago" WHERE LTRIM(RTRIM(Tournament_Country)) = "Port-of-Spain, TRI";
UPDATE atp SET Tournament_Country = "Tunisia" WHERE LTRIM(RTRIM(Tournament_Country)) = "Tunis";
UPDATE atp SET Tournament_Country = "United Arab Emirates" WHERE LTRIM(RTRIM(Tournament_Country)) LIKE "%U.A.E.%";
UPDATE atp SET Tournament_Country = "United States" WHERE LTRIM(RTRIM(Tournament_Country)) LIKE "%U.S.A%";
UPDATE atp SET Tournament_Country = "United States" WHERE LTRIM(RTRIM(Tournament_Country)) LIKE "%U.S.A.%";
UPDATE atp SET Tournament_Country = "United Kingdom" WHERE LTRIM(RTRIM(Tournament_Country)) = "Birmingham, UK";
UPDATE atp SET Tournament_Country = "United States" WHERE LTRIM(RTRIM(Tournament_Country)) = "Carson, CA, United S";
UPDATE atp SET Tournament_Country = "Uruguay" WHERE LTRIM(RTRIM(Tournament_Country)) = "Montevideo, Uraguay";
UPDATE atp SET Tournament_Country = "France" WHERE LTRIM(RTRIM(Tournament_Country)) = "Uriage, Uriage";
UPDATE atp SET Tournament_Country = "Uruguay" WHERE LTRIM(RTRIM(Tournament_Country)) = "Montevideo, URU";
UPDATE atp SET Tournament_Country = "Uruguay" WHERE LTRIM(RTRIM(Tournament_Country)) = "Urugay";
UPDATE atp SET Tournament_Country = "United States" WHERE LTRIM(RTRIM(Tournament_Country)) LIKE "%USA%";
UPDATE atp SET Tournament_Country = "Uzbekistan" WHERE LTRIM(RTRIM(Tournament_Country)) = "Tashkent, Uzb.";
UPDATE atp SET Tournament_Country = "Spain" WHERE LTRIM(RTRIM(Tournament_Country)) = "Valldoreix, Valldoreix";
UPDATE atp SET Tournament_Country = "Venezuela, Bolivarian Republic of" WHERE LTRIM(RTRIM(Tournament_Country)) = "Venezeuela";
UPDATE atp SET Tournament_Country = "Venezuela, Bolivarian Republic of" WHERE LTRIM(RTRIM(Tournament_Country)) LIKE "%Venezuela%";
UPDATE atp SET Tournament_Country = "Australia" WHERE LTRIM(RTRIM(Tournament_Country)) = "Sale, Victoria";
UPDATE atp SET Tournament_Country = "Viet Nam" WHERE LTRIM(RTRIM(Tournament_Country)) LIKE "%Vietnam%";
UPDATE atp SET Tournament_Country = "Colombia" WHERE LTRIM(RTRIM(Tournament_Country)) = "Villavicencio";
UPDATE atp SET Tournament_Country = "United Kingdom" WHERE LTRIM(RTRIM(Tournament_Country)) = "Wrexham, Wales";
UPDATE atp SET Tournament_Country = "New Zealand" WHERE LTRIM(RTRIM(Tournament_Country)) = "Wellington";
UPDATE atp SET Tournament_Country = "Australia" WHERE LTRIM(RTRIM(Tournament_Country)) = "West Perth";
UPDATE atp SET Tournament_Country = "Germany" WHERE LTRIM(RTRIM(Tournament_Country)) = "Wetzlar, Wetzlar";
UPDATE atp SET Tournament_Country = "Curaçao" WHERE LTRIM(RTRIM(Tournament_Country)) = "Willemstad";
UPDATE atp SET Tournament_Country = "Poland" WHERE LTRIM(RTRIM(Tournament_Country)) = "Wroclaw, Wrocklaw";
UPDATE atp SET Tournament_Country = "China" WHERE LTRIM(RTRIM(Tournament_Country)) = "Wuhan";
UPDATE atp SET Tournament_Country = "Serbia" WHERE LTRIM(RTRIM(Tournament_Country)) = "Belgrade, Yug.";
UPDATE atp SET Tournament_Country = "Serbia" WHERE LTRIM(RTRIM(Tournament_Country)) LIKE "%Yugoslavia%";
UPDATE atp SET Tournament_Country = "Botswana" WHERE Tournament_Country = "TBA" AND Tournament_Name LIKE "%Botswana%";
UPDATE atp SET Tournament_Country = "Egypt" WHERE Tournament_Country = "TBA" AND Tournament_Name LIKE "%Egypt%";
UPDATE atp SET Tournament_Country = "France" WHERE Tournament_Country = "TBA" AND Tournament_Name LIKE "%France%";
UPDATE atp SET Tournament_Country = "United Kingdom" WHERE Tournament_Country = "TBA" AND Tournament_Name LIKE "%Great Britain%";
UPDATE atp SET Tournament_Country = "India" WHERE Tournament_Country = "TBA" AND Tournament_Name LIKE "%India%";
UPDATE atp SET Tournament_Country = "Italy" WHERE Tournament_Country = "TBA" AND Tournament_Name LIKE "%Italy%";
UPDATE atp SET Tournament_Country = "United States" WHERE Tournament_Country = "TBA" AND Tournament_Name LIKE "%U.S.A.%";
UPDATE atp SET Tournament_Country = "Zimbabwe" WHERE Tournament_Country = "TBA" AND Tournament_Name LIKE "%Zimbabwe%";


ALTER TABLE Atp ADD INDEX (LinkPlayer,Tournament_Name,Tournament_Country,Tournament_Date,Round,Opponent);
ALTER TABLE Countries ADD INDEX (Country_Name);

DROP TABLE IF EXISTS Players; 
CREATE TABLE Players(ID_Player int NOT NULL AUTO_INCREMENT, Player_Name varchar(100), Born_Country varchar(100), Heigth int(3), Hand varchar(100), LinkPlayer varchar(200), PRIMARY KEY (ID_Player));

INSERT INTO Players(Player_Name, Heigth, Hand, LinkPlayer, Born_Country)
SELECT atp.Player_Name, atp.Heigth, atp.Hand, atp.LinkPlayer, IF(atp.Born_Country IN (SELECT countries.Country_Name FROM countries) , atp.Born_Country, LTRIM(RTRIM(SUBSTRING_INDEX(atp.Born_Country, ',' ,-1))))
FROM atp
GROUP BY atp.LinkPlayer;

INSERT INTO Players(Player_Name) 
SELECT DISTINCT Opponent FROM atp WHERE Opponent NOT IN (SELECT Player_Name FROM Players);


UPDATE Players SET Players.Born_Country = NULL WHERE LENGTH(Players.Born_Country) = 0;
UPDATE Players SET Born_Country = "United States" WHERE LENGTH(Born_Country)=2;
UPDATE Players SET Players.Heigth = NULL WHERE Players.Heigth = 0 OR LENGTH(Players.Heigth) = 0;
UPDATE Players SET Players.Hand = NULL WHERE Players.Hand = 'null' OR LENGTH(Players.Hand) = 0;
ALTER TABLE Players ADD CONSTRAINT fk_BornCountry FOREIGN KEY (Born_Country) REFERENCES Countries(Country_Name) ON DELETE RESTRICT ON UPDATE CASCADE;

DROP TABLE IF EXISTS Tournaments;
CREATE TABLE Tournaments(ID_Tournament int NOT NULL AUTO_INCREMENT, Tournament_Name varchar(100), Tournament_Country varchar(100), Tournament_Start_Date DATE, Tournament_End_Date DATE, Ground varchar(10), Prize varchar(100), PRIMARY KEY (ID_Tournament));

INSERT INTO Tournaments(Tournament_Name,Ground,Prize, Tournament_Country, Tournament_Start_Date,Tournament_End_Date)
SELECT atp.Tournament_Name, atp.Ground, atp.Prize, IF(atp.Tournament_Country IN (SELECT countries.Country_Name FROM countries), atp.Tournament_Country, LTRIM(RTRIM(SUBSTRING_INDEX(atp.Tournament_Country, ',' ,-1)))), LTRIM(RTRIM(SUBSTRING_INDEX(atp.Tournament_Date, '-' ,1))), LTRIM(RTRIM(SUBSTRING_INDEX(atp.Tournament_Date, '-' ,-1))) 
FROM atp
GROUP BY atp.Tournament_Name, atp.Tournament_Date;


UPDATE Tournaments SET Tournaments.Tournament_Country = NULL WHERE LENGTH(Tournaments.Tournament_Country) = 0;
ALTER TABLE Tournaments ADD CONSTRAINT fk_TournamentCountry FOREIGN KEY (Tournament_Country) REFERENCES Countries(Country_Name) ON DELETE RESTRICT ON UPDATE CASCADE;

UPDATE Tournaments SET Tournaments.Ground = NULL WHERE LENGTH(Tournaments.Ground) = 0 OR Tournaments.Ground = "null" OR Tournaments.Ground = "NULL";
UPDATE Tournaments SET Tournaments.Prize = NULL WHERE LENGTH(Tournaments.Prize) = 0 OR Tournaments.Prize = "null" OR Tournaments.Prize = "NULL";

ALTER TABLE players ADD INDEX (LinkPlayer);
ALTER TABLE tournaments ADD INDEX (Tournament_Name, Tournament_Start_Date, Tournament_End_Date);

DROP TABLE IF EXISTS Games;
CREATE TABLE Games(ID_Game int NOT NULL AUTO_INCREMENT, ID_Tournament int(5), ID_Player int(3), Round varchar(100), Opponent_Rank int(4), Opponent varchar(100), Result varchar(100), Score varchar(100), PRIMARY KEY (ID_Game));

INSERT INTO Games(ID_Tournament,ID_Player,Round,Opponent_Rank,Opponent,Result,Score)
SELECT Tournaments.ID_Tournament, Players.ID_Player, atp.Round, atp.Opponent_Rank, atp.Opponent, atp.Result, atp.Score 
FROM atp, Players, Tournaments
WHERE atp.LinkPlayer = players.LinkPlayer 
	AND atp.Tournament_Name = Tournaments.Tournament_Name 
	AND LTRIM(RTRIM(SUBSTRING_INDEX(atp.Tournament_Date, '-' ,1))) = Tournaments.Tournament_Start_Date
	AND LTRIM(RTRIM(SUBSTRING_INDEX(atp.Tournament_Date, '-' ,-1))) = Tournaments.Tournament_End_Date
GROUP BY atp.Player_Name,atp.Born_Country,atp.Heigth,atp.Hand,atp.LinkPlayer,atp.Tournament_Name,atp.Tournament_Country,atp.Tournament_Date,atp.Ground,atp.Prize,atp.Round,atp.Opponent_Rank,atp.Opponent,atp.Result,atp.Score;

UPDATE Games SET Games.Round = NULL WHERE LENGTH(Games.Round) = 0 OR Games.Round = "null" OR Games.Round = "NULL";
UPDATE Games SET Games.Opponent_Rank = NULL WHERE LENGTH(Games.Opponent_Rank) = 0 OR Games.Opponent_Rank = 0;
UPDATE Games SET Games.Result = NULL WHERE LENGTH(Games.Result) = 0;
UPDATE Games SET Games.Score = NULL WHERE LENGTH(Games.Score) = 0 OR Games.Score = "null" OR Games.Score = "NULL";

ALTER TABLE Players ADD INDEX (ID_Player, Player_Name);
ALTER TABLE Players ADD INDEX (ID_Player);
ALTER TABLE Players ADD INDEX (Player_Name);

ALTER TABLE Games ADD INDEX (ID_Game, ID_Tournament, Opponent, Round);
ALTER TABLE Games ADD INDEX (ID_Player);

DROP TABLE IF EXISTS Unique_Game;
CREATE TABLE Unique_Games(ID_Game int(10), ID_Tournament int(5), ID_Player int(3), Round varchar(100), Opponent_Rank int(11), ID_Opponent int(3), Opponent varchar(100), Result varchar(100), Score varchar(100), Duplicado varchar(10),PRIMARY KEY (ID_Game));

INSERT INTO Unique_Games(ID_Game, ID_Tournament,ID_Player,Round,Opponent_Rank,ID_Opponent, Opponent,Result,Score)
SELECT Games.ID_Game, Games.ID_Tournament, Games.ID_Player, Games.Round, Games.Opponent_Rank, Players.ID_Player, Games.Opponent, Games.Result, Games.Score 
FROM Games, Players
WHERE Games.Opponent = Players.Player_Name
GROUP BY Games.ID_Game;


UPDATE Unique_Games SET Unique_Games.Opponent = NULL WHERE LENGTH(Unique_Games.Opponent) = 0 OR Unique_Games.Opponent = "null" OR Unique_Games.Opponent = "NULL" OR Unique_Games.Opponent = "bye";
UPDATE Unique_Games SET Unique_Games.ID_Opponent = NULL WHERE Unique_Games.Opponent IS NULL; 
DELETE FROM Players WHERE Player_Name = "bye";

ALTER TABLE Unique_Games ADD INDEX (ID_Tournament, Round, ID_Opponent);
ALTER TABLE Unique_Games ADD INDEX (ID_Player);
ALTER TABLE Unique_Games ADD INDEX (ID_Opponent);

UPDATE Unique_Games UG1 SET Duplicado = "X" WHERE ID_Opponent IN (SELECT ID_Player 
								 FROM Unique_Games UG2 
								 WHERE UG1.ID_Tournament = UG2.ID_Tournament 
								     AND UG1.Round = UG2.Round 
								     AND UG1.ID_Game > UG2.ID_Game);

DELETE FROM Unique_Games WHERE Duplicado = "X";
ALTER TABLE Unique_Games DROP COLUMN Duplicado;

ALTER TABLE Unique_Games ADD CONSTRAINT fk_G_ID_Player FOREIGN KEY (ID_Player) REFERENCES Players(ID_Player) ON DELETE RESTRICT ON UPDATE CASCADE;
ALTER TABLE Unique_Games ADD CONSTRAINT fk_G_ID_Opponent FOREIGN KEY (ID_Opponent) REFERENCES Players(ID_Player) ON DELETE RESTRICT ON UPDATE CASCADE;
ALTER TABLE Unique_Games ADD CONSTRAINT fk_G_ID_Tournament FOREIGN KEY (ID_Tournament) REFERENCES Tournaments(ID_Tournament) ON DELETE RESTRICT ON UPDATE CASCADE;

DROP TABLE atp;
DROP TABLE Games;
ALTER TABLE Unique_Games RENAME TO Games;

# 1. Para cada país | a) Número de jogadores | b) Número de torneios | c) Número de rondas
SELECT countries.Country_Name as CountryName, 

       (SELECT Count(Players.Born_Country) 
        FROM Players 
        WHERE Players.Born_Country = Countries.Country_Name) as TotalPlayers, 
        
       (SELECT Count(Tournaments.Tournament_Country) 
        FROM Tournaments 
        WHERE Tournaments.Tournament_Country = Countries.Country_Name) as TotalTournaments,
        
       (Select Count(*) 
        FROM Tournaments, Games
        WHERE Games.ID_Tournament = Tournaments.ID_Tournament 
        AND Tournaments.Tournament_Country = Countries.Country_Name) as TotalGames
        
FROM Countries
GROUP BY Country_Name;


# 2. Lista dos 10 melhores jogadores com a sua % de jogos vencidos, por ordem por %
SELECT Players.Player_Name,
       SUM(CASE
             WHEN Games.Result = 'W' AND Games.ID_Player = Players.ID_Player THEN 1
             WHEN Games.Result = 'L' AND Games.ID_Opponent = Players.ID_Player THEN 1
             ELSE 0
           END) / COUNT(*) * 100 AS Win_Percentage
FROM Players
INNER JOIN Games ON Players.ID_Player = Games.ID_Player OR Players.ID_Player = Games.ID_Opponent
WHERE (Games.ID_Player < 9960 AND Games.ID_Opponent < 9960 AND Players.ID_Player < 9960)
GROUP BY Players.ID_Player
HAVING COUNT(*) > 30
ORDER BY Win_Percentage DESC
LIMIT 10;


# 3. Lista dos 10 melhores jogadores canhotos com a sua % de jogos vencidos em torneios do Grand Slam
SELECT Players.Player_Name,
       SUM(CASE
             WHEN Games.Result = 'W' AND Games.ID_Player = Players.ID_Player THEN 1
             WHEN Games.Result = 'L' AND Games.ID_Opponent = Players.ID_Player THEN 1
             ELSE 0
           END) / COUNT(*) * 100 AS Win_Percentage
FROM Players
INNER JOIN Games ON Players.ID_Player = Games.ID_Player OR Players.ID_Player = Games.ID_Opponent
INNER JOIN Tournaments ON Games.ID_Tournament = Tournaments.ID_Tournament
WHERE Players.Hand LIKE '%Left%' 
	AND (Tournaments.Tournament_Name = "Wimbledon"
         OR Tournaments.Tournament_Name = "US Open"
         OR Tournaments.Tournament_Name = "Roland Garros" 
         OR Tournaments.Tournament_Name = "Australian Open")
	AND (Games.ID_Player < 9960 AND Games.ID_Opponent < 9960 AND Players.ID_Player < 9960)
GROUP BY Players.ID_Player
HAVING COUNT(*) > 30
ORDER BY Win_Percentage DESC
LIMIT 10;


# 4. Lista dos 5 melhores jogadores com os seus jogos vencidos em Hard Ground
SELECT Players.Player_Name,
       SUM(CASE
             WHEN Games.Result = 'W' AND Games.ID_Player = Players.ID_Player THEN 1
             WHEN Games.Result = 'L' AND Games.ID_Opponent = Players.ID_Player THEN 1
             ELSE 0
           END) AS Wins_Hard_Ground
FROM Players
INNER JOIN Games ON Players.ID_Player = Games.ID_Player OR Players.ID_Player = Games.ID_Opponent
INNER JOIN Tournaments ON Games.ID_Tournament = Tournaments.ID_Tournament 
WHERE Tournaments.Ground = 'Hard'
	AND (Games.ID_Player < 9960 AND Games.ID_Opponent < 9960 AND Players.ID_Player < 9960)
GROUP BY Players.ID_Player
ORDER BY Wins_Hard_Ground DESC
LIMIT 5;

