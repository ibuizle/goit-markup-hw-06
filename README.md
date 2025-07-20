.main-title-item {
   font-weight: 700;
font-size: 36px;
line-height: 111%;
text-align: left;
}

.button{
    margin: 36px auto 0;
}

.mobile-menu{
display: none;
}


.main-header .logo {
    margin-right: 120px;
    padding: 240px 0;
    
}

.main-nav {
    display: flex;
    gap: 40px;
}


    .burger-btn{
        display: none;
    }

    .menu,
    .address{
    display: flex;
    align-items: center;
    gap: 40px;
    }

    /* .contact-list{
    display: flex;
    align-items: center;
    gap: 150px;
    } */


    .main-nav{
        display: flex;
        align-items: center;
    }

    .email {
    font-weight: 400;
    font-size: 12px;
    line-height: 1.17;
    letter-spacing: 0.04em;
    color: #434455;
    display: block;
    transition: color 250ms cubic-bezier(0.4, 0, 0.2, 1);
}

    .contact-list{
    display: flex;
    flex-direction: column;
    align-items: flex-end;
    gap: 12px;
    font-style: normal;
    }


.hero {
    max-width: 1440px;
    background-image:
    linear-gradient(rgba(46, 47, 66, 0.7), rgba(46, 47, 66, 0.7)),
    url(../images/people-officecompressed_tablet.png);
}

@media screen and (min-resolution:2x ) {
    .hero{
        background-image:
    linear-gradient(rgba(46, 47, 66, 0.7), rgba(46, 47, 66, 0.7)),
    url(../images/people-officecompressed_tablet_x2.png);
    }
}

.key-features {
    font-weight: 400;
font-size: 16px;
}

.effective{
/* font-weight: 700;
font-size: 56px;
line-height: 107%;
letter-spacing: 0.02em; */
font-weight: 700;
font-size: 56px;
line-height: 107%;
letter-spacing: 0.02em;
text-align: center;

}


    .features-section{
        padding-top: 96px;
        padding-bottom: 96px;
    }

    .features-item {
        width: calc((100% - 24px) / 2);
    }

    .features-list{
        padding-top: 96px;
        padding-right: 24px;
        padding-left: 24px;
        padding-bottom: 72px;
    }


    .team-list{
        flex-direction: row;
        flex-wrap: wrap;
        justify-content: center;
        gap: 24px;
    }

    .team-card {
    width: 100%;
    max-width: 264px;
    }

.portfolio-card{
    box-shadow: none;
}


.portfolio-card:hover{
    box-shadow: 0px 1px 6px rgba(46, 47, 66, 0.08),
        0px 1px 1px rgba(46, 47, 66, 0.16),
        0px 2px 1px rgba(46, 47, 66, 0.08);
}


    .app-list{
        flex-direction: row;
        flex-wrap: wrap;
        justify-content: center;
        gap: 24px;
    }

    .portfolio-card {
    flex-basis: calc((100% - 24px) / 2);
    }

    .subscribe-container {
    width: auto;
    margin-left: auto;
    padding: 0;
    }

    .subscribe-form {
    flex-direction: row;
    gap: 24px;
    align-items: center;
    justify-content: center;
    }

    .subscribe-title {
    text-align: left;
    }

    .footer-container{
    display: flex;
    flex-wrap: nowrap;
    justify-content: center;
    gap: 24px;
    min-width: 768px;
    margin: 0 auto;
    padding: 0 16px;
    
  }

  .footer-logo-box{
    margin-right: 120px;
    min-width: 264px;
}

/* .footer-row-top,
.footer-btn{
    flex-basis: calc((100% - 72px) / 4);
    }
} */

/* .footer-top-row{
    display: flex;
    flex-direction: row;
    gap: 24px;
}

.footer-btn{
    display: flex;
    flex-direction: row;
    gap: 24px;
} */

.modal-window{
    width: 408px;
    min-height: 584px;
}
