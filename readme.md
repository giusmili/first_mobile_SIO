# &lt;/&gt; Cours first mobile
Dans ce cours on apprend comment travailler une page web à partir d'un écran mobile
Une méthode inverse par rapport au responsive design.
La référence dans ce cas ne sera pas d'abord le desk pour le mobile mais, d'abord le mobile et après le desk.
Pour la partie desk on fera un minimum de media queris pour créer l'interface adaptée aux écrans pc.

```css
    /* media queris desk */

@media screen and (orientation: landscape) {
    .main-content{
        display: flex;
        height: 100vh;
    }
    .main-content-flex, .main-content-image{
        height: 100vh;
        flex: 0 1 50vw;
    }
}
/* media for desk */
@media screen and (min-width: 80.0rem) {
    .main-content-flex{
        flex: 0 1 40vw;
    }
}
```