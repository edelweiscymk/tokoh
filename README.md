    body {
        background-color: #fbf7f0;
        font-family: 'Inter', sans-serif;
        color: #2c221a;
        line-height: 1.5;
        padding: 2rem 1.5rem;
    }

    .container {
        max-width: 1200px;
        margin: 0 auto;
        background: #fefcf8;
        padding: 2.5rem 2.5rem 3rem;
        border-radius: 2.5rem;
        box-shadow: 0 12px 30px rgba(0, 0, 0, 0.04);
    }

    /* header / navbar */
    .navbar {
        display: flex;
        flex-wrap: wrap;
        align-items: center;
        justify-content: space-between;
        margin-bottom: 2.5rem;
        padding-bottom: 1.2rem;
        border-bottom: 1px solid #ede6dc;
    }

    .logo {
        font-size: 1.9rem;
        font-weight: 700;
        letter-spacing: -0.02em;
        color: #3d2c1e;
    }
    .logo span {
        font-weight: 300;
        color: #b48b6e;
    }

    .nav-links {
        display: flex;
        flex-wrap: wrap;
        gap: 2rem;
        font-weight: 500;
        color: #4a382a;
    }
    .nav-links a {
        text-decoration: none;
        color: inherit;
        font-size: 1rem;
        letter-spacing: 0.3px;
        border-bottom: 2px solid transparent;
        padding-bottom: 4px;
        transition: 0.2s;
    }
    .nav-links a:hover {
        border-bottom-color: #b48b6e;
        color: #2c1f15;
    }
    .nav-links .new-badge {
        background: #c7a587;
        color: white;
        font-size: 0.65rem;
        padding: 0.2rem 0.7rem;
        border-radius: 20px;
        margin-left: 6px;
        vertical-align: middle;
        font-weight: 600;
        letter-spacing: 0.3px;
    }

    /* hero / tagline */
    .hero {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
        align-items: center;
        margin-bottom: 3rem;
        gap: 1.5rem;
    }

    .hero-text {
        max-width: 600px;
    }

    .hero-text h1 {
        font-size: 3rem;
        font-weight: 700;
        line-height: 1.1;
        letter-spacing: -0.02em;
        color: #2c1f15;
    }
    .hero-text h1 .highlight {
        display: block;
        color: #b48b6e;
        font-weight: 300;
        font-size: 2.2rem;
        margin-top: 0.25rem;
    }
    .hero-text p {
        margin-top: 1.2rem;
        font-size: 1rem;
        color: #4f3d2e;
        max-width: 460px;
    }

    .hero-image {
        background: #e6d8ca;
        width: 140px;
        height: 140px;
        border-radius: 50%;
        display: flex;
        align-items: center;
        justify-content: center;
        font-size: 3.5rem;
        color: #7a604a;
        box-shadow: 0 8px 18px rgba(0,0,0,0.03);
    }

    /* best sellers */
    .best-sellers {
        margin: 3.5rem 0 3rem;
    }

    .best-sellers h2 {
        font-size: 1.8rem;
        font-weight: 600;
        letter-spacing: -0.01em;
        margin-bottom: 1.8rem;
        color: #2c1f15;
    }

    .product-grid {
        display: grid;
        grid-template-columns: repeat(4, 1fr);
        gap: 1.8rem;
    }

    .product-card {
        background: #f9f4ed;
        padding: 1.5rem 1rem 1.2rem;
        border-radius: 2rem;
        text-align: center;
        transition: 0.2s ease;
        box-shadow: 0 2px 6px rgba(0,0,0,0.01);
    }
    .product-card:hover {
        background: #f5ede3;
    }

    .product-card .icon {
        font-size: 2.8rem;
        margin-bottom: 0.5rem;
        display: block;
    }

    .product-card h3 {
        font-weight: 700;
        font-size: 1.1rem;
        letter-spacing: -0.2px;
        margin-bottom: 0.3rem;
        color: #2c1f15;
    }

    .product-card p {
        font-size: 0.9rem;
        color: #5b4a3a;
        margin-top: 0.3rem;
        line-height: 1.4;
    }

    /* magic section */
    .magic-section {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
        align-items: center;
        background: #f3ece2;
        padding: 2.2rem 2.5rem;
        border-radius: 2.5rem;
        margin: 3rem 0 3.5rem;
    }

    .magic-section h2 {
        font-size: 2rem;
        font-weight: 600;
        letter-spacing: -0.02em;
        color: #2c1f15;
    }

    .magic-section p {
        max-width: 380px;
        font-size: 1rem;
        color: #4f3d2e;
        margin-top: 0.3rem;
    }

    .magic-btn {
        background: #2c1f15;
        color: white;
        border: none;
        padding: 0.9rem 2.2rem;
        border-radius: 60px;
        font-weight: 600;
        font-size: 1rem;
        cursor: default;
        letter-spacing: 0.3px;
        transition: 0.15s;
        box-shadow: 0 4px 8px rgba(0,0,0,0.03);
    }

    /* call to action */
    .cta-box {
        background: #e8dbce;
        padding: 2.8rem 2.5rem;
        border-radius: 2.5rem;
        margin-top: 1.5rem;
        display: flex;
        flex-wrap: wrap;
        align-items: center;
        justify-content: space-between;
    }

    .cta-box h3 {
        font-size: 2rem;
        font-weight: 600;
        letter-spacing: -0.02em;
        color: #2c1f15;
    }
    .cta-box p {
        font-size: 1rem;
        max-width: 400px;
        color: #3f3124;
        margin: 0.5rem 0 0.2rem;
    }

    .cta-btn {
        background: #2c1f15;
        color: white;
        border: none;
        padding: 1rem 2.8rem;
        border-radius: 60px;
        font-weight: 600;
        font-size: 1.1rem;
        letter-spacing: 0.3px;
        cursor: default;
        box-shadow: 0 4px 10px rgba(0,0,0,0.02);
    }

    /* footer / alamat & hp */
    .footer-info {
        margin-top: 3.8rem;
        padding-top: 2rem;
        border-top: 1px solid #e2d6c8;
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
        align-items: center;
        gap: 1rem;
        font-size: 0.95rem;
        color: #4d3d2f;
    }

    .footer-info .address {
        max-width: 540px;
        line-height: 1.6;
    }
    .footer-info .phone {
        font-weight: 600;
        background: #f3ece2;
        padding: 0.5rem 1.5rem;
        border-radius: 40px;
        letter-spacing: 0.3px;
    }

    /* responsive */
    @media (max-width: 900px) {
        .product-grid {
            grid-template-columns: repeat(2, 1fr);
        }
        .container {
            padding: 1.8rem;
        }
        .hero-text h1 {
            font-size: 2.4rem;
        }
    }

    @media (max-width: 600px) {
        .navbar {
            flex-direction: column;
            align-items: start;
            gap: 0.8rem;
        }
        .nav-links {
            gap: 1.2rem;
        }
        .product-grid {
            grid-template-columns: 1fr;
        }
        .magic-section, .cta-box {
            flex-direction: column;
            align-items: start;
            gap: 1.5rem;
        }
        .cta-box {
            align-items: start;
        }
        .footer-info {
            flex-direction: column;
            align-items: start;
        }
    }
</style>    body {
        background-color: #fbf7f0;
        font-family: 'Inter', sans-serif;
        color: #2c221a;
        line-height: 1.5;
        padding: 2rem 1.5rem;
    }

    .container {
        max-width: 1200px;
        margin: 0 auto;
        background: #fefcf8;
        padding: 2.5rem 2.5rem 3rem;
        border-radius: 2.5rem;
        box-shadow: 0 12px 30px rgba(0, 0, 0, 0.04);
    }

    /* header / navbar */
    .navbar {
        display: flex;
        flex-wrap: wrap;
        align-items: center;
        justify-content: space-between;
        margin-bottom: 2.5rem;
        padding-bottom: 1.2rem;
        border-bottom: 1px solid #ede6dc;
    }

    .logo {
        font-size: 1.9rem;
        font-weight: 700;
        letter-spacing: -0.02em;
        color: #3d2c1e;
    }
    .logo span {
        font-weight: 300;
        color: #b48b6e;
    }

    .nav-links {
        display: flex;
        flex-wrap: wrap;
        gap: 2rem;
        font-weight: 500;
        color: #4a382a;
    }
    .nav-links a {
        text-decoration: none;
        color: inherit;
        font-size: 1rem;
        letter-spacing: 0.3px;
        border-bottom: 2px solid transparent;
        padding-bottom: 4px;
        transition: 0.2s;
    }
    .nav-links a:hover {
        border-bottom-color: #b48b6e;
        color: #2c1f15;
    }
    .nav-links .new-badge {
        background: #c7a587;
        color: white;
        font-size: 0.65rem;
        padding: 0.2rem 0.7rem;
        border-radius: 20px;
        margin-left: 6px;
        vertical-align: middle;
        font-weight: 600;
        letter-spacing: 0.3px;
    }

    /* hero / tagline */
    .hero {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
        align-items: center;
        margin-bottom: 3rem;
        gap: 1.5rem;
    }

    .hero-text {
        max-width: 600px;
    }

    .hero-text h1 {
        font-size: 3rem;
        font-weight: 700;
        line-height: 1.1;
        letter-spacing: -0.02em;
        color: #2c1f15;
    }
    .hero-text h1 .highlight {
        display: block;
        color: #b48b6e;
        font-weight: 300;
        font-size: 2.2rem;
        margin-top: 0.25rem;
    }
    .hero-text p {
        margin-top: 1.2rem;
        font-size: 1rem;
        color: #4f3d2e;
        max-width: 460px;
    }

    .hero-image {
        background: #e6d8ca;
        width: 140px;
        height: 140px;
        border-radius: 50%;
        display: flex;
        align-items: center;
        justify-content: center;
        font-size: 3.5rem;
        color: #7a604a;
        box-shadow: 0 8px 18px rgba(0,0,0,0.03);
    }

    /* best sellers */
    .best-sellers {
        margin: 3.5rem 0 3rem;
    }

    .best-sellers h2 {
        font-size: 1.8rem;
        font-weight: 600;
        letter-spacing: -0.01em;
        margin-bottom: 1.8rem;
        color: #2c1f15;
    }

    .product-grid {
        display: grid;
        grid-template-columns: repeat(4, 1fr);
        gap: 1.8rem;
    }

    .product-card {
        background: #f9f4ed;
        padding: 1.5rem 1rem 1.2rem;
        border-radius: 2rem;
        text-align: center;
        transition: 0.2s ease;
        box-shadow: 0 2px 6px rgba(0,0,0,0.01);
    }
    .product-card:hover {
        background: #f5ede3;
    }

    .product-card .icon {
        font-size: 2.8rem;
        margin-bottom: 0.5rem;
        display: block;
    }

    .product-card h3 {
        font-weight: 700;
        font-size: 1.1rem;
        letter-spacing: -0.2px;
        margin-bottom: 0.3rem;
        color: #2c1f15;
    }

    .product-card p {
        font-size: 0.9rem;
        color: #5b4a3a;
        margin-top: 0.3rem;
        line-height: 1.4;
    }

    /* magic section */
    .magic-section {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
        align-items: center;
        background: #f3ece2;
        padding: 2.2rem 2.5rem;
        border-radius: 2.5rem;
        margin: 3rem 0 3.5rem;
    }

    .magic-section h2 {
        font-size: 2rem;
        font-weight: 600;
        letter-spacing: -0.02em;
        color: #2c1f15;
    }

    .magic-section p {
        max-width: 380px;
        font-size: 1rem;
        color: #4f3d2e;
        margin-top: 0.3rem;
    }

    .magic-btn {
        background: #2c1f15;
        color: white;
        border: none;
        padding: 0.9rem 2.2rem;
        border-radius: 60px;
        font-weight: 600;
        font-size: 1rem;
        cursor: default;
        letter-spacing: 0.3px;
        transition: 0.15s;
        box-shadow: 0 4px 8px rgba(0,0,0,0.03);
    }

    /* call to action */
    .cta-box {
        background: #e8dbce;
        padding: 2.8rem 2.5rem;
        border-radius: 2.5rem;
        margin-top: 1.5rem;
        display: flex;
        flex-wrap: wrap;
        align-items: center;
        justify-content: space-between;
    }

    .cta-box h3 {
        font-size: 2rem;
        font-weight: 600;
        letter-spacing: -0.02em;
        color: #2c1f15;
    }
    .cta-box p {
        font-size: 1rem;
        max-width: 400px;
        color: #3f3124;
        margin: 0.5rem 0 0.2rem;
    }

    .cta-btn {
        background: #2c1f15;
        color: white;
        border: none;
        padding: 1rem 2.8rem;
        border-radius: 60px;
        font-weight: 600;
        font-size: 1.1rem;
        letter-spacing: 0.3px;
        cursor: default;
        box-shadow: 0 4px 10px rgba(0,0,0,0.02);
    }

    /* footer / alamat & hp */
    .footer-info {
        margin-top: 3.8rem;
        padding-top: 2rem;
        border-top: 1px solid #e2d6c8;
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
        align-items: center;
        gap: 1rem;
        font-size: 0.95rem;
        color: #4d3d2f;
    }

    .footer-info .address {
        max-width: 540px;
        line-height: 1.6;
    }
    .footer-info .phone {
        font-weight: 600;
        background: #f3ece2;
        padding: 0.5rem 1.5rem;
        border-radius: 40px;
        letter-spacing: 0.3px;
    }

    /* responsive */
    @media (max-width: 900px) {
        .product-grid {
            grid-template-columns: repeat(2, 1fr);
        }
        .container {
            padding: 1.8rem;
        }
        .hero-text h1 {
            font-size: 2.4rem;
        }
    }

    @media (max-width: 600px) {
        .navbar {
            flex-direction: column;
            align-items: start;
            gap: 0.8rem;
        }
        .nav-links {
            gap: 1.2rem;
        }
        .product-grid {
            grid-template-columns: 1fr;
        }
        .magic-section, .cta-box {
            flex-direction: column;
            align-items: start;
            gap: 1.5rem;
        }
        .cta-box {
            align-items: start;
        }
        .footer-info {
            flex-direction: column;
            align-items: start;
        }
    }
</style>
