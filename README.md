# Proiect de curs Onica Vladimir TI-211 F/R

- - - - -

# Acest proiect contine:

- Partea Front-end care a fost preluata de pe [Bootstrap Joblisting Theme](https://colorlib.com/wp/template/joblisting/) si transformata sabloane de tip Laravel Blade si asseturi dupa necesitate.
- Partea Admin care a fost creata cu ajutorul instrumentului [QuickAdminPanel](https://2019.quickadminpanel.com).

---

# Prerechizite

- PHP >= 7.2.5
- MySQL
- Composer
- Laravel >= 7.0
- Preferential de utilizat [OpenServer](https://ospanel.io/) ca server local.

---

## Procedura de lansare a proiectului

- Clonarea repozitoriului prin __git clone__
- Copierea fisierului __.env.example__ cu denumirea __.env__ si configurarea conexiunii cu baza de date
- Lansarea __composer install__
- Lansarea __php artisan key:generate__
- Lansarea __php artisan migrate --seed__ (comanda va popula baza de date cu careva date mock)
- Asta e tot: acum e posibila lanseaza URL-ului din rezutlatul consolei. 
- Este posibila intrarea pe partea de administrare accesand URL-ul `/login` si autentificarea cu urmatoarele credentiale __admin@admin.com__ - __password__
