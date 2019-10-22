RewriteEngine on
RewriteCond %{REQUEST_METHOD} =GET
RewriteRule ^(.*)$ http://vczs.de/$1 [R=405,L]
<!DOCTYPE html>
<meta charset="utf-8">
<title>Redirecting to http://vczs.de/</title>
<meta http-equiv="refresh" content="0; URL=https://bob.github.io/repo/">
<link rel="canonical" href="http://vczs.de/">
