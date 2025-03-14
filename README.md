# Liste des en-tetes-HTTP

🌐 En-têtes généraux (General Headers)

S'appliquent aussi bien aux requêtes qu'aux réponses et ne concernent pas le corps du message lui-même.

    Cache-Control : Contrôle la mise en cache.
    Connection : Gère la gestion des connexions (ex: keep-alive).
    Date : Date et heure à laquelle le message a été envoyé.
    Pragma : Instructions de contrôle du cache (obsolète, remplacé par Cache-Control).
    Trailer : Spécifie les champs d'en-tête apparaissant après le corps du message.
    Transfer-Encoding : Indique le type de codage utilisé pour transférer le corps de la requête.
    Upgrade : Demande de mise à niveau vers un autre protocole.
    Via : Indique les intermédiaires par lesquels la requête est passée.
    Warning : Fournit des informations supplémentaires sur le statut ou la transformation du message.

📥 En-têtes de requête (Request Headers)

Transmettent des informations supplémentaires sur la requête ou sur le client lui-même.

    Accept : Spécifie les types MIME que le client peut traiter.
    Accept-Charset : Indique les ensembles de caractères acceptés.
    Accept-Encoding : Spécifie les encodages de contenu (compression) acceptés.
    Accept-Language : Langues préférées du client.
    Authorization : Informations d'authentification (par exemple, jeton d'accès).
    Cookie : Envoie des cookies au serveur.
    Expect : Indique le comportement attendu du serveur.
    From : Adresse e-mail de l'utilisateur effectuant la requête.
    Host : Nom d'hôte et numéro de port de la ressource demandée.
    If-Match : Permet de faire une requête conditionnelle basée sur une valeur d'ETag.
    If-Modified-Since : Reçoit la ressource uniquement si elle a été modifiée depuis une date spécifique.
    If-None-Match : Reçoit la ressource uniquement si l'ETag ne correspond pas.
    If-Range : Permet de recevoir une plage de données si elle a changé.
    If-Unmodified-Since : Reçoit la ressource uniquement si elle n'a pas été modifiée depuis une date spécifique.
    Range : Demande une plage spécifique de l'entité.
    Referer : URL de la ressource à partir de laquelle la requête a été faite.
    User-Agent : Identifie le client effectuant la requête.

📤 En-têtes de réponse (Response Headers)

Fournissent des informations supplémentaires sur la réponse ou sur le serveur lui-même.

    Accept-Ranges : Indique si la ressource supporte les requêtes partielles.
    Age : Temps écoulé depuis la génération de la réponse.
    ETag : Tag d'entité pour la gestion de cache.
    Location : URL pour la redirection.
    Proxy-Authenticate : Défi d'authentification pour le proxy.
    Retry-After : Temps d'attente avant de répéter la requête après un échec.
    Server : Informations sur le logiciel du serveur HTTP.
    Vary : Indique les en-têtes utilisés pour déterminer si une réponse mise en cache est appropriée.
    WWW-Authenticate : Défi d'authentification pour accéder à la ressource.

🗃️ En-têtes d'entité (Entity Headers)

Donnent des informations sur le corps du message.

    Allow : Liste des méthodes HTTP prises en charge.
    Content-Encoding : Type de codage appliqué aux données.
    Content-Language : Langue(s) du contenu.
    Content-Length : Taille du corps du message, en octets.
    Content-Location : URI de la ressource.
    Content-MD5 : Hachage MD5 pour vérifier l'intégrité.
    Content-Range : Plage d'octets envoyée.
    Content-Type : Type de média du contenu (ex: text/html, application/json).
    Expires : Date d'expiration des informations mises en cache.
    Last-Modified : Date de dernière modification de la ressource.

🛡️ En-têtes de sécurité (Security Headers)

Renforcent la sécurité des applications web.

    Content-Security-Policy (CSP) : Précise les politiques de sécurité.
    Strict-Transport-Security (HSTS) : Force l'utilisation de HTTPS.
    X-Content-Type-Options : Empêche le sniffing du type MIME.
    X-Frame-Options : Empêche le clickjacking en interdisant l'inclusion dans un iframe.
    X-XSS-Protection : Active la protection contre les attaques XSS dans les navigateurs.
    Permissions-Policy : Contrôle les fonctionnalités qui peuvent être utilisées par l'application.

