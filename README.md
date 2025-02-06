# bulk_editor_SQL_findandreplace_text
Bulk editor SQL find and replace text in article

STRINGA SQL

UPDATE wpqq_posts  (QUI INSERISCI IL NOME DELLA TABLE GIUSTA DI RIFERIMENTO DEL TUO PHPMYADMIN (wp-post per esempio))

SET post_content = REPLACE(post_content, 'QUI IL TESTO DA TROVARE', 'QUI IL TESTO DA MODIFICARE O LASCIARE VUOTO SE VUOI CANCELLARE');
