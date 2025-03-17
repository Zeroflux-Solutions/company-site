====
> Info: Duration: 2m 56s 111ms | ~$0.0083 | Prompt Tokens: 12,797 (cached: 0) | Completion Tokens: 10,653 (reasoning: 0) | Model: gpt-4o-mini | Adapter: OpenAI

````html
<!-- file: index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ZeroFlux Solutions</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
</head>
<body>
    <header class="header">
        <div class="container header-container">
            <div class="logo">
                <span class="logo-text">ZeroFlux</span>
                <span class="logo-accent">Solutions</span>
            </div>
            <nav class="nav">
                <button class="mobile-menu-toggle" aria-label="Toggle menu">
                    <span></span>
                    <span></span>
                    <span></span>
                </button>
                <ul class="nav-list">
                    <li><a href="#home" class="nav-link">Home</a></li>
                    <li><a href="#services" class="nav-link">Services</a></li>
                    <li><a href="#about" class="nav-link">About</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <main>
        <section id="home" class="hero">
            <div class="container">
                <div class="hero-content">
                    <h1 class="hero-title">Robust Rust Solutions for Modern Challenges</h1>
                    <p class="hero-subtitle">Scalable backends, performant desktop applications, and elegant websites built with Native Web Components and Rust</p>
                    <div class="hero-buttons">
                        <a href="#services" class="btn btn-primary">Our Services</a>
                    </div>
                </div>
                <div class="hero-image">
                    <div class="code-block">
                        <pre><code>
fn main() {
    println!("Welcome to ZeroFlux Solutions");

    let services = vec![
        "Rust Backends",
        "Desktop Apps",
        "Web Development"
    ];

    for service in services {
        deliver_excellence(service);
    }
}
                        </code></pre>
                    </div>
                </div>
            </div>
        </section>
        <section id="services" class="services">
            <div class="container">
                <h2 class="section-title">Our Services</h2>
                <p class="section-subtitle">Leveraging Rust's performance and reliability for your business needs</p>
                <div class="services-grid">
                    <div class="service-card">
                        <div class="service-icon">
                            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="2" y="2" width="20" height="8" rx="2" ry="2"></rect><rect x="2" y="14" width="20" height="8" rx="2" ry="2"></rect><line x1="6" y1="6" x2="6.01" y2="6"></line><line x1="6" y1="18" x2="6.01" y2="18"></line></svg>
                        </div>
                        <h3>Rust Backends</h3>
                        <p>High-performance, secure, and scalable backend systems built with Rust's safety guarantees and blazing speed.</p>
                    </div>
                    <div class="service-card">
                        <div class="service-icon">
                            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="3" width="18" height="18" rx="2" ry="2"></rect><line x1="3" y1="9" x2="21" y2="9"></line><line x1="9" y1="21" x2="9" y2="9"></line></svg>
                        </div>
                        <h3>Desktop Applications</h3>
                        <p>Cross-platform desktop applications with native performance and memory safety, powered by Rust.</p>
                    </div>
                    <div class="service-card">
                        <div class="service-icon">
                            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polygon points="12 2 2 7 12 12 22 7 12 2"></polygon><polyline points="2 17 12 22 22 17"></polyline><polyline points="2 12 12 17 22 12"></polyline></svg>
                        </div>
                        <h3>Web Development</h3>
                        <p>Modern, responsive websites using native web components with Rust-powered backends for unparalleled performance and reliability.</p>
                    </div>
                </div>
            </div>
        </section>
        <section id="about" class="about">
            <div class="container">
                <div class="about-content">
                    <h2 class="section-title">About ZeroFlux</h2>
                    <p>At ZeroFlux Solutions, we're passionate about building robust, efficient, and maintainable software systems using Rust. Our team combines deep technical expertise with a commitment to excellence.</p>
                    <p>Founded by Rust enthusiasts, we believe in leveraging the language's unique capabilities to solve complex problems with elegant solutions.</p>
                </div>
                <div class="about-image">
                    <div class="tech-stack">
                        <div class="tech-item">
                            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 128 128" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M62.96.242c-.232.135-1.203 1.528-2.16 3.097-2.4 3.94-2.426 3.942-5.65.55-2.098-2.208-2.605-2.612-3.28-2.607-.44.002-.995.152-1.235.332-.24.18-.916 1.612-1.504 3.183-1.346 3.6-1.41 3.715-2.156 3.86-.46.086-1.343-.407-3.463-1.929-1.565-1.125-3.1-2.045-3.411-2.045-1.291 0-1.655.706-2.27 4.4-.78 4.697-.754 4.681-4.988 2.758-1.71-.776-3.33-1.41-3.603-1.41-.274 0-.792.293-1.15.652-.652.652-.653.655-.475 4.246l.178 3.595-.68.364c-.602.322-1.017.283-3.684-.348-3.48-.822-4.216-.8-4.92.15l-.516.693.692 2.964c.38 1.63.745 3.2.814 3.487.067.287-.05.746-.26 1.02-.348.448-.717.49-3.94.44-5.452-.086-5.761.382-3.51 5.3.718 1.56 1.305 2.98 1.305 3.15 0 .898-.717 1.224-3.794 1.727-1.722.28-3.218.51-3.326.51-.107 0-.43.235-.717.522-.937.936-.671 1.816 1.453 4.814 2.646 3.735 2.642 3.75-1.73 5.421-4.971 1.902-5.072 2.37-1.287 5.96 3.525 3.344 3.53 3.295-.461 5.804C.208 62.8.162 62.846.085 63.876c-.093 1.253-.071 1.275 3.538 3.48 3.57 2.18 3.57 2.246.067 5.56C-.078 76.48.038 77 5.013 78.877c4.347 1.64 4.353 1.66 1.702 5.394-1.502 2.117-1.981 3-1.981 3.653 0 1.223.637 1.535 4.44 2.174 3.206.54 3.92.857 3.92 1.741 0 .182-.588 1.612-1.307 3.177-2.236 4.87-1.981 5.275 3.31 5.275 4.93 0 4.799-.15 3.737 4.294-.8 3.35-.813 3.992-.088 4.715.554.556 1.6.494 4.87-.289 2.499-.596 2.937-.637 3.516-.328l.66.354-.177 3.594c-.178 3.593-.177 3.595.475 4.248.358.36.884.652 1.165.652.282 0 1.903-.63 3.604-1.404 4.22-1.916 4.194-1.932 4.973 2.75.617 3.711.977 4.4 2.294 4.4.327 0 1.83-.88 3.34-1.958 2.654-1.893 3.342-2.19 4.049-1.74.182.115.89 1.67 1.572 3.455 1.003 2.625 1.37 3.31 1.929 3.576 1.062.51 1.72.1 4.218-2.62 3.016-3.286 3.14-3.27 5.602.72 2.72 4.406 3.424 4.396 6.212-.089 2.402-3.864 2.374-3.862 5.621-.47 2.157 2.25 2.616 2.61 3.343 2.61.464 0 1.019-.175 1.23-.388.214-.213.92-1.786 1.568-3.496.649-1.71 1.321-3.2 1.495-3.31.687-.436 1.398-.13 4.048 1.752 1.56 1.108 3.028 1.96 3.377 1.96 1.296 0 1.764-.92 2.302-4.535.46-3.082.554-3.378 1.16-3.685.596-.302.954-.2 3.75 1.07 1.701.77 3.323 1.402 3.604 1.402.282 0 .816-.302 1.184-.672l.672-.67-.184-3.448c-.177-3.29-.16-3.468.364-3.943.54-.488.596-.486 3.615.204 3.656.835 4.338.857 5.025.17.671-.67.664-.818-.254-4.69-1.03-4.346-1.168-4.19 3.78-4.19 3.374 0 3.75-.049 4.18-.523.718-.793.547-1.702-.896-4.779-.729-1.55-1.32-2.96-1.315-3.135.024-.914.743-1.227 4.065-1.767 2.033-.329 3.553-.71 3.829-.96.923-.833.584-1.918-1.523-4.873-2.642-3.703-2.63-3.738 1.599-5.297 5.064-1.866 5.209-2.488 1.419-6.09-3.51-3.335-3.512-3.317.333-5.677 4.648-2.853 4.655-3.496.082-6.335-3.933-2.44-3.93-2.406-.405-5.753 3.78-3.593 3.678-4.063-1.295-5.965-4.388-1.679-4.402-1.72-1.735-5.38 1.588-2.18 1.982-2.903 1.982-3.65 0-1.306-.586-1.598-4.436-2.22-3.216-.52-3.924-.835-3.924-1.75 0-.174.588-1.574 1.307-3.113 1.406-3.013 1.604-4.22.808-4.94-.428-.387-1-.443-4.067-.392-3.208.054-3.618.008-4.063-.439-.486-.488-.48-.557.278-3.725.931-3.88.935-3.975.17-4.694-.777-.73-1.262-.718-4.826.121-2.597.612-3.027.653-3.617.337l-.67-.36.185-3.582.186-3.58-.67-.67c-.369-.37-.891-.67-1.163-.67-.27 0-1.884.64-3.583 1.421-2.838 1.306-3.143 1.393-3.757 1.072-.612-.32-.714-.637-1.237-3.829-.603-3.693-.977-4.412-2.288-4.412-.311 0-1.853.925-3.426 2.055-2.584 1.856-2.93 2.032-3.574 1.807-.533-.186-.843-.59-1.221-1.599-.28-.742-.817-2.172-1.194-3.177-.762-2.028-1.187-2.482-2.328-2.482-.637 0-1.213.458-3.28 2.604-3.25 3.375-3.261 3.374-5.65-.545C66.073 1.78 65.075.382 64.81.24c-.597-.32-1.3-.32-1.85.002m2.96 11.798c2.83 2.014 1.326 6.75-2.144 6.75-3.368 0-5.064-4.057-2.66-6.36 1.358-1.3 3.304-1.459 4.805-.39m-3.558 12.507c1.855.705 2.616.282 6.852-3.8l3.182-3.07 1.347.18c4.225.56 12.627 4.25 17.455 7.666 4.436 3.14 10.332 9.534 12.845 13.93l.537.942-2.38 5.364c-1.31 2.95-2.382 5.673-2.382 6.053 0 .878.576 2.267 1.13 2.726.234.195 2.457 1.265 4.939 2.378l4.51 2.025.178 1.148c.23 1.495.26 5.167.052 6.21l-.163.816h-2.575c-2.987 0-2.756-.267-2.918 3.396-.118 2.656-.76 4.124-2.22 5.075-2.377 1.551-6.304 1.27-7.97-.57-.255-.284-.752-1.705-1.105-3.16-1.03-4.254-2.413-6.64-5.193-8.965-.878-.733-1.595-1.418-1.595-1.522 0-.102.965-.915 2.145-1.803 4.298-3.24 6.77-7.012 7.04-10.747.519-7.126-5.158-13.767-13.602-15.92-2.002-.51-2.857-.526-27.624-.526-14.057 0-25.56-.092-25.56-.204 0-.263 3.125-3.295 4.965-4.816 5.054-4.178 11.618-7.465 18.417-9.22l2.35-.61 3.34 3.387c1.839 1.863 3.64 3.5 4.003 3.637M20.3 46.34c1.539 1.008 2.17 3.54 1.26 5.062-1.405 2.356-4.966 2.455-6.373.178-2.046-3.309 1.895-7.349 5.113-5.24m90.672.13c4.026 2.454.906 8.493-3.404 6.586-2.877-1.273-2.97-5.206-.155-6.64 1.174-.6 2.523-.579 3.56.053M32.163 61.5v15.02h-13.28l-.526-2.285c-1.036-4.5-1.472-9.156-1.211-12.969l.182-2.679 4.565-2.047c2.864-1.283 4.706-2.262 4.943-2.625 1.038-1.584.94-2.715-.518-5.933l-.68-1.502h6.523V61.5M70.39 47.132c2.843.74 4.345 2.245 4.349 4.355.002 1.55-.765 2.52-2.67 3.38-1.348.61-1.562.625-10.063.708l-8.686.084v-8.92h7.782c6.078 0 8.112.086 9.288.393m-2.934 21.554c1.41.392 3.076 1.616 3.93 2.888.898 1.337 1.423 3.076 2.667 8.836 1.05 4.87 1.727 6.46 3.62 8.532 2.345 2.566 1.8 2.466 13.514 2.466 5.61 0 10.198.09 10.198.2 0 .197-3.863 4.764-4.03 4.764-.048 0-2.066-.422-4.484-.939-6.829-1.458-7.075-1.287-8.642 6.032l-1.008 4.702-.91.448c-1.518.75-6.453 2.292-9.01 2.82-4.228.87-8.828 1.162-12.871.821-6.893-.585-16.02-3.259-16.377-4.8-.075-.327-.535-2.443-1.018-4.704-.485-2.26-1.074-4.404-1.31-4.764-1.13-1.724-2.318-1.83-7.547-.674-1.98.44-3.708.796-3.84.796-.248 0-3.923-4.249-3.923-4.535 0-.09 8.728-.194 19.396-.23l19.395-.066.07-6.89c.05-4.865-.018-6.997-.23-7.25-.234-.284-1.485-.358-6.011-.358H53.32v-8.36l6.597.001c3.626.002 7.02.12 7.539.264M37.57 100.02c3.084 1.88 1.605 6.804-2.043 6.8-3.74 0-5.127-4.88-1.94-6.826 1.055-.643 2.908-.63 3.983.026m56.48.206c1.512 1.108 2.015 3.413 1.079 4.95-2.46 4.034-8.612.827-6.557-3.419 1.01-2.085 3.695-2.837 5.478-1.53"/></svg>
                            <span>Rust</span>
                        </div>
                        <div class="tech-item">
                            <svg version="1.0" xmlns="http://www.w3.org/2000/svg"
                             width="24" height="24" viewBox="0 0 108 108" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" preserveAspectRatio="xMidYMid meet">
                            <g transform="translate(0.000000,108.000000) scale(0.100000,-0.100000)"
                            fill="#000000" stroke="none">
                            <path d="M233 1062 c-11 -7 1 -29 142 -270 l48 -83 -26 -26 -26 -26 -61 36
                            c-34 21 -66 35 -71 31 -22 -13 -5 -35 51 -66 59 -32 68 -46 54 -82 -5 -14 -30
                            -16 -175 -16 -162 0 -169 -1 -169 -20 0 -19 7 -20 169 -20 145 0 170 -2 175
                            -16 14 -36 5 -50 -54 -82 -56 -31 -70 -49 -53 -65 3 -4 34 9 69 28 34 19 66
                            35 71 35 5 0 15 -11 23 -24 12 -23 8 -33 -45 -123 -115 -195 -136 -235 -131
                            -249 3 -8 10 -14 15 -14 5 0 55 78 110 174 l102 174 32 -9 c18 -5 33 -9 34 -9
                            2 0 3 -34 3 -75 0 -68 2 -75 20 -75 18 0 20 7 20 74 l0 74 32 11 c17 6 35 8
                            39 4 10 -10 96 -154 155 -258 40 -72 50 -83 65 -75 16 9 7 28 -82 182 -54 95
                            -99 175 -99 178 0 3 7 14 16 25 15 20 16 19 83 -17 37 -21 71 -35 75 -31 16
                            16 1 34 -54 65 -59 32 -68 46 -54 82 5 14 30 16 175 16 162 0 169 1 169 20 0
                            19 -7 20 -169 20 -145 0 -170 2 -175 16 -14 36 -5 50 54 82 56 31 70 49 53 65
                            -3 4 -35 -9 -70 -29 l-64 -35 -28 23 -28 24 99 169 c54 94 97 174 95 179 -2 6
                            -8 11 -15 14 -12 4 -17 -4 -132 -202 -38 -65 -73 -123 -79 -129 -5 -5 -21 -7
                            -35 -3 -25 6 -26 9 -26 81 0 68 -2 75 -20 75 -18 0 -20 -7 -20 -74 0 -76 -6
                            -87 -48 -86 -11 1 -50 58 -113 167 -52 92 -100 168 -105 170 -5 1 -14 -1 -21
                            -5z m377 -384 c33 -17 51 -35 68 -68 27 -54 27 -82 2 -137 -52 -117 -219 -118
                            -277 -3 -13 24 -23 56 -23 70 0 49 42 113 90 138 24 12 56 22 70 22 14 0 46
                            -10 70 -22z"/>
                            <path d="M514 556 c-10 -26 4 -48 28 -44 33 4 33 52 0 56 -13 2 -25 -3 -28
                            -12z"/>
                            <path d="M514 976 c-10 -26 4 -48 28 -44 17 2 23 10 23 28 0 18 -6 26 -23 28
                            -13 2 -25 -3 -28 -12z"/>
                            <path d="M154 766 c-10 -26 4 -48 28 -44 17 2 23 10 23 28 0 18 -6 26 -23 28
                            -13 2 -25 -3 -28 -12z"/>
                            <path d="M874 766 c-10 -26 4 -48 28 -44 17 2 23 10 23 28 0 18 -6 26 -23 28
                            -13 2 -25 -3 -28 -12z"/>
                            <path d="M157 354 c-10 -11 -9 -42 3 -49 20 -12 51 6 48 28 -3 22 -36 35 -51
                            21z"/>
                            <path d="M874 346 c-10 -26 4 -48 28 -44 17 2 23 10 23 28 0 18 -6 26 -23 28
                            -13 2 -25 -3 -28 -12z"/>
                            <path d="M523 143 c-15 -6 -17 -39 -3 -48 20 -12 51 6 48 28 -3 22 -22 30 -45
                            20z"/>
                            </g>
                            </svg>
                            <span>Axum</span>
                        </div>
                        <div class="tech-item">
                            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" viewBox="0 0 128 128"><path fill="#ffc131" d="M86.242 46.547a12.19 12.19 0 0 1-24.379 0c0-6.734 5.457-12.191 12.191-12.191a12.19 12.19 0 0 1 12.188 12.191zm0 0"/><path fill="#24c8db" d="M41.359 81.453a12.19 12.19 0 1 1 24.383 0c0 6.734-5.457 12.191-12.191 12.191S41.36 88.187 41.36 81.453zm0 0"/><path fill="#ffc131" d="M99.316 85.637a46.5 46.5 0 0 1-16.059 6.535 32.675 32.675 0 0 0 1.797-10.719 33.3 33.3 0 0 0-.242-4.02 32.69 32.69 0 0 0 6.996-3.418 32.7 32.7 0 0 0 12.066-14.035 32.71 32.71 0 0 0-21.011-44.934 32.72 32.72 0 0 0-33.91 10.527 32.85 32.85 0 0 0-1.48 1.91 54.32 54.32 0 0 0-17.848 5.184A46.536 46.536 0 0 1 60.25 2.094a46.53 46.53 0 0 1 26.34-.375c8.633 2.418 16.387 7.273 22.324 13.984s9.813 15 11.16 23.863a46.537 46.537 0 0 1-20.758 46.071zM30.18 41.156l11.41 1.402a32.44 32.44 0 0 1 1.473-6.469 46.44 46.44 0 0 0-12.883 5.066zm0 0"/><path fill="#24c8db" d="M28.207 42.363a46.49 46.49 0 0 1 16.188-6.559 32.603 32.603 0 0 0-2.004 11.297 32.56 32.56 0 0 0 .188 3.512 32.738 32.738 0 0 0-6.859 3.371A32.7 32.7 0 0 0 23.652 68.02c-2.59 5.742-3.461 12.113-2.52 18.34s3.668 12.051 7.844 16.77 9.617 8.129 15.684 9.824 12.496 1.605 18.512-.262a32.72 32.72 0 0 0 15.402-10.266 34.9 34.9 0 0 0 1.484-1.918 54.283 54.283 0 0 0 17.855-5.223 46.528 46.528 0 0 1-8.723 16.012 46.511 46.511 0 0 1-21.918 14.609 46.53 46.53 0 0 1-26.34.375 46.6 46.6 0 0 1-22.324-13.984A46.56 46.56 0 0 1 7.453 88.434a46.53 46.53 0 0 1 3.582-26.098 46.533 46.533 0 0 1 17.172-19.973zm69.074 44.473c-.059.035-.121.066-.18.102.059-.035.121-.066.18-.102zm0 0"/></svg>
                            <span>Tauri</span>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    <footer class="footer">
        <div class="container">
            <div class="footer-content">
                <div class="footer-logo">
                    <span class="logo-text">ZeroFlux</span>
                    <span class="logo-accent">Solutions</span>
                    <p>The one Stop Shop for application design</p>
                    <p>Building the future with rust</p>
                </div>
                <div class="footer-links">
                    <div class="footer-column">
                        <h3>Company</h3>
                        <ul>
                            <li><a href="#about">About</a></li>
                        </ul>
                    </div>
                    <div class="footer-column">
                        <h3>Services</h3>
                        <ul>
                            <li><a href="#services">Rust Backends</a></li>
                            <li><a href="#services">Desktop Apps</a></li>
                            <li><a href="#services">Web Development</a></li>
                            <li><a href="#">Consulting</a></li>
                        </ul>
                    </div>
                    <div class="footer-column">
                        <h3>Connect</h3>
                        <ul>
                            <li><a href="#">GitHub</a></li>
                            <li><a href="#">LinkedIn</a></li>
                        </ul>
                    </div>
                </div>
            </div>
            <div class="footer-bottom">
                <p>&copy; 2025 ZeroFlux Solutions. All rights reserved.</p>
            </div>
        </div>
    </footer>
    <script src="script.js"></script>
</body>
</html>
````


````css
/* file: styles.css */
:root {
    --color-background: #0a1929;
    --color-foreground: #f8fafc;
    --color-primary: #0ea5e9;
    --color-primary-hover: #0284c7;
    --color-secondary: #10b981;
    --color-secondary-hover: #059669;
    --color-muted: #64748b;
    --color-card: #112240;
    --color-card-hover: #1e3a8a;
    --color-border: #1e293b;
    --color-code-bg: #1e293b;

    --shadow-sm: 0 1px 2px 0 rgba(0, 0, 0, 0.05);
    --shadow-md:
        0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06);
    --shadow-lg:
        0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);

    --font-sans:
        "Inter", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
        Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
    --font-mono:
        ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas,
        "Liberation Mono", "Courier New", monospace;

    --radius-sm: 0.125rem;
    --radius-md: 0.375rem;
    --radius-lg: 0.5rem;
    --radius-full: 9999px;

    --header-height: 4rem;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
    scroll-padding-top: var(--header-height);
}

body {
    font-family: var(--font-sans);
    background-color: var(--color-background);
    color: var(--color-foreground);
    line-height: 1.5;
    overflow-x: hidden;
}

a {
    color: inherit;
    text-decoration: none;
}

ul {
    list-style: none;
}

img {
    max-width: 100%;
    height: auto;
}

button {
    cursor: pointer;
    font-family: inherit;
}

.container {
    width: 100%;
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 1.5rem;
}

h1,
h2,
h3,
h4,
h5,
h6 {
    font-weight: 700;
    line-height: 1.2;
}

.section-title {
    font-size: 2.5rem;
    margin-bottom: 1rem;
    position: relative;
    display: inline-block;
}

.section-title::after {
    content: "";
    position: absolute;
    bottom: -0.5rem;
    left: 0;
    width: 60px;
    height: 4px;
    background-color: var(--color-primary);
    border-radius: var(--radius-full);
}

.section-subtitle {
    font-size: 1.125rem;
    color: var(--color-muted);
    margin-bottom: 3rem;
    max-width: 600px;
}

.btn {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    padding: 0.75rem 1.5rem;
    border-radius: var(--radius-md);
    font-weight: 500;
    transition: all 0.2s ease;
    border: none;
}

.btn-primary {
    background-color: var(--color-primary);
    color: white;
}

.btn-primary:hover {
    background-color: var(--color-primary-hover);
}

.btn-secondary {
    background-color: transparent;
    border: 1px solid var(--color-secondary);
    color: var(--color-secondary);
}

.btn-secondary:hover {
    background-color: var(--color-secondary);
    color: white;
}

.header {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: var(--header-height);
    background-color: rgba(10, 25, 41, 0.8);
    backdrop-filter: blur(10px);
    z-index: 100;
    border-bottom: 1px solid var(--color-border);
}

.header-container {
    display: flex;
    align-items: center;
    justify-content: space-between;
    height: 100%;
}

.logo {
    font-size: 1.5rem;
    font-weight: 700;
}

.logo-text {
    color: var(--color-foreground);
}

.logo-accent {
    color: var(--color-primary);
}

.nav-list {
    display: flex;
    gap: 2rem;
}

.nav-link {
    position: relative;
    font-weight: 500;
    transition: color 0.2s ease;
}

.nav-link:hover {
    color: var(--color-primary);
}

.mobile-menu-toggle {
    display: none;
    background: none;
    border: none;
    width: 2rem;
    height: 1.5rem;
    position: relative;
    z-index: 101;
}

.mobile-menu-toggle span {
    display: block;
    width: 100%;
    height: 2px;
    background-color: var(--color-foreground);
    position: absolute;
    left: 0;
    transition: all 0.3s ease;
}

.mobile-menu-toggle span:nth-child(1) {
    top: 0;
}

.mobile-menu-toggle span:nth-child(2) {
    top: 50%;
    transform: translateY(-50%);
}

.mobile-menu-toggle span:nth-child(3) {
    bottom: 0;
}

.hero {
    padding: 8rem 0 5rem;
    position: relative;
    overflow: hidden;
}

.hero .container {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 4rem;
}

.hero-title {
    font-size: 3.5rem;
    margin-bottom: 1.5rem;
    line-height: 1.1;
}

.hero-subtitle {
    font-size: 1.25rem;
    color: var(--color-muted);
    margin-bottom: 2.5rem;
}

.hero-buttons {
    display: flex;
    gap: 1rem;
}

.hero-image {
    display: flex;
    justify-content: center;
    align-items: center;
}

.code-block {
    background-color: var(--color-code-bg);
    border-radius: var(--radius-md);
    padding: 1.5rem;
    width: 100%;
    box-shadow: var(--shadow-lg);
    position: relative;
    overflow: hidden;
}

.code-block::before {
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 4px;
    background: linear-gradient(
        90deg,
        var(--color-primary),
        var(--color-secondary)
    );
}

.code-block pre {
    font-family: var(--font-mono);
    font-size: 0.875rem;
    color: #e2e8f0;
    overflow-x: auto;
}

.services {
    padding: 6rem 0;
    background-color: rgba(17, 34, 64, 0.3);
}

.services-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
    margin-top: 2rem;
}

.service-card {
    background-color: var(--color-card);
    border-radius: var(--radius-md);
    padding: 2rem;
    transition:
        transform 0.3s ease,
        box-shadow 0.3s ease;
    border: 1px solid var(--color-border);
}

.service-card:hover {
    transform: translateY(-5px);
    box-shadow: var(--shadow-lg);
    border-color: var(--color-primary);
}

.service-icon {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    width: 3rem;
    height: 3rem;
    background-color: rgba(14, 165, 233, 0.1);
    border-radius: var(--radius-md);
    margin-bottom: 1.5rem;
    color: var(--color-primary);
}

.service-card h3 {
    font-size: 1.5rem;
    margin-bottom: 1rem;
}

.service-card p {
    color: var(--color-muted);
}

.about {
    padding: 6rem 0;
}

.about .container {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 4rem;
    align-items: center;
}

.about-content p {
    margin-bottom: 1.5rem;
    color: var(--color-muted);
}

.tech-stack {
    display: grid;
    grid-template-rows: 1fr 1fr 1fr;
    gap: 1.5rem;
}

.tech-item {
    display: flex;
    align-items: center;
    gap: 0.75rem;
    background-color: var(--color-card);
    padding: 1rem;
    border-radius: var(--radius-md);
    border: 1px solid var(--color-border);
    transition: all 0.2s ease;
}

.tech-item:hover {
    border-color: var(--color-primary);
    transform: translateY(-2px);
}

.tech-item svg {
    color: var(--color-primary);
}
.footer {
    padding: 4rem 0 2rem;
    background-color: #071320;
    border-top: 1px solid var(--color-border);
}

.footer-content {
    display: flex;
    justify-content: space-between;
    margin-bottom: 3rem;
}

.footer-logo {
    max-width: 300px;
}

.footer-logo p {
    margin-top: 1rem;
    color: var(--color-muted);
}

.footer-links {
    display: flex;
    gap: 4rem;
}

.footer-column h3 {
    font-size: 1.125rem;
    margin-bottom: 1.5rem;
}

.footer-column ul {
    display: flex;
    flex-direction: column;
    gap: 0.75rem;
}

.footer-column a {
    color: var(--color-muted);
    transition: color 0.2s ease;
}

.footer-column a:hover {
    color: var(--color-primary);
}

.footer-bottom {
    padding-top: 2rem;
    border-top: 1px solid var(--color-border);
    text-align: center;
    color: var(--color-muted);
    font-size: 0.875rem;
}

@media (max-width: 1024px) {
    .section-title {
        font-size: 2rem;
    }

    .hero-title {
        font-size: 2.5rem;
    }
}

@media (max-width: 768px) {
    .hero .container,
    .about .container {
        grid-template-columns: 1fr;
        gap: 3rem;
    }

    .hero {
        padding: 7rem 0 4rem;
    }

    .mobile-menu-toggle {
        display: block;
    }

    .nav-list {
        position: fixed;
        top: 0;
        right: -100%;
        width: 70%;
        height: 100vh;
        background-color: var(--color-background);
        flex-direction: column;
        justify-content: center;
        align-items: center;
        transition: right 0.3s ease;
        z-index: 100;
        border-left: 1px solid var(--color-border);
    }

    .nav-list.active {
        right: 0;
    }

    .footer-content {
        flex-direction: column;
        gap: 3rem;
    }

    .footer-links {
        flex-wrap: wrap;
        gap: 2rem;
    }
}

@media (max-width: 480px) {
    .hero-title {
        font-size: 2rem;
    }

    .hero-buttons {
        flex-direction: column;
    }

    .tech-stack {
        grid-template-columns: 1fr;
    }

    .footer-links {
        flex-direction: column;
    }
}

````


