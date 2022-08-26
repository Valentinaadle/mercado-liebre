# mercado-liebre
@medi (min-width: 361px){
    main section article .description{
        display: block;
    }

    main section article{
        box-shadow: 0px 0px 10px rgb(100, 100, 100);
    }

    main section div.products{
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
        justify-content: space-between;
        align-items: flex-start;
        width: 100vh;
    }
    
    main section div.products article{
        width: 45%;
    }

    .price,
    .discount{
        width: 50%;
    }
}



@medi  (min-width: 769px) {

.article { box-shadow: 0px 0px 10px rgb(100, 100, 100);
width: 25vh; } 
.burger-menu {
    display: none;
}
.titulares {
    display: block;
}
main {
    display: flex;
    }
.titulares {
    display: flex;
    flex-direction: row;
    justify-content: flex-start;
}
}