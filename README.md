# TuotekuvastoApp

TuotekuvastoApp käyttää MVC arkkitehtuuria (Model-View-Controller)
Model tiedostot sisältävät datan, controller älyn ja view sisältää näkymät.
Data löytyy wwwroot/product.json tiedostosta ja se muutetaan olioksi Product.cs Mallin avulla.
HomeController.cs tiedoston metodi GetProducts muuttaa products.json tiedoston datan Product olioita sisältäväksi listaksi.

Product.cshtml sisältää koodin joka luo käyttöliittymän joka näyttää products.json tiedoston datan käyttäjäystävällisessä muodossa.
