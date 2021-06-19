<h2>Run test technique :</h2>

Step:
<li>1. download or clone project</li>
<li>2. Go to the folder application using cd</li>
<li>3. Run composer install on your cmd or terminal</li>
<li>4. Copy .env.example file to .env on root folder. 
    You can type copy .env.example .env if using command prompt Windows 
     or cp .env.example .env if using terminal Ubuntu</li>
<li>5. Open your .env file and change the database name (DB_DATABASE)</li>
<li>6. Run php artisan key:generate</li>
<li>7. Run php artisan migrate</li>
<li>8. php artisan db:seed</li>
<li>9.Run php artisan serve</li>
