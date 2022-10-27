# MYSQL-DATABASE

SAUVEGARDER UNE BASE SQL de MYSQL

mysqldump -root --password=(votre mot de passe) (dossier mysql exemple: dupont) > dupont.sql

SAUVERGARDER TOUTES LES BASES MYSQL

mysqldump -root --password=(votre mot de passe) --all-databases > all.sql

**************************************************************************

IMPORTER UNE BASE SQL dans MYSQL

mysql -root --password=(votre mot de passe) (dossier mysql exemple: dupont) < dupont.sql

IMPORTER TOUTES LES BASES MYSQL

mysql -root --password=(votre mot de passe) --all-databases < all.sql
