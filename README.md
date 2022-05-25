# UW_Portfolio
img { 
    max-width: 100%;
    height: auto;
}

.container {
    width: 970px;
    max-width: 100%;
    padding: 0px;
    /* Shorhand margin with three values = top, right & left, bottom */
    margin: 0px 0px 0px;
}

.header-main .container {
    display: flex;
    align-items: center;
    flex-wrap: wrap;
}

.main-nav {
    /* add in main nav selector to attempt to get text pushed right */
    display: flex;
    justify-content: flex-end;

}

.main-nav ul {
    margin: 1em 0 .5em;
    text-align: center;
}

.main-nav li {
    display: inline-flex;
}

.main-nav a {
    display: inline-flex;
    justify-content: flex-end;
}