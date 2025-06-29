<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>XTOPro Info</title>
    <style>
        /* Reset and Base Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

  body {
            font-family: 'Roboto', sans-serif; /* Modern font */
            line-height: 1.6;
            color: #000000; /* Black text for readability */
            background: url('https://images.unsplash.com/photo-1507525428034-b723cf961d3e?q=80&w=2073&auto=format&fit=crop') no-repeat center center fixed;
            background-size: cover; /* Full-screen background */
        }

 .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

 /* Header and Navigation */
        header {
            background: rgba(44, 62, 80, 0.9); /* Semi-transparent for background visibility */
            color: #fff;
            padding: 1rem 0;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

 nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

   nav h1 {
            font-family: 'Montserrat', sans-serif; /* Elegant font for title */
            font-size: 2.2rem;
            font-weight: 700;
            letter-spacing: 2px;
            text-transform: uppercase;
            color: #ffffff;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
        }
 nav ul {
            list-style: none;
            display: flex;
            gap: 20px;
        }

 nav ul li a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
            font-size: 1.1rem;
            transition: color 0.3s;
        }

 nav ul li a:hover {
            color: #9b59b6; /* Lovely purple hover */
        }

 /* Sections */
        section {
            padding: 60px 0;
            background: rgba(255, 255, 255, 0.85); /* Semi-transparent white for readability */
            border-radius: 8px;
            margin: 20px 0;
        }
        section h1, section h2, section h3, section h4, section h5, section h6 {
            margin-bottom: 20px;
            color: #2c3e50; /* Darker color for headings */
            font-family: 'Montserrat', sans-serif;
        }

 section#intro {
            text-align: center;
        }

 section#work, section#about, section#elements, section#contact {
            background: rgba(255, 255, 255, 0.9);
        }

  /* Contact Form */
        form {
            display: grid;
            gap: 15px;
            max-width: 600px;
            margin: 0 auto;
        }

 input, textarea, select, button {
            padding: 10px;
            width: 100%;
            border: 1px solid #ccc;
            border-radius: 4px;
            font-family: 'Roboto', sans-serif;
            color: #000000;
        }

 button, .button {
            background: #6c757d; /* Stylish gray */
            color: #fff;
            border: none;
            cursor: pointer;
            transition: transform 0.2s, background 0.3s, box-shadow 0.3s;
            position: relative;
            overflow: hidden;
            border-radius: 8px;
            padding: 12px 20px;
            font-size: 1.1rem;
            font-weight: 500;
        }

 button:hover, .button:hover {
            background: #9b59b6; /* Lovely purple on hover */
            transform: scale(1.05);
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
        }

 button::after, .button::after {
            content: '';
            position: absolute;
            top: 50%;
 left: 50%;
            width: 0;
            height: 0;
            background: rgba(255, 255, 255, 0.3);
            border-radius: 50%;
            transform: translate(-50%, -50%);
            transition: width 0.5s, height 0.5s;
        }

 button:hover::after, .button:hover::after {
            width: 200px;
            height: 200px;
        }

 button.disabled, .button.disabled {
            background: #ccc;
            cursor: not-allowed;
            transform: none;
            box-shadow: none;
        }

 /* Elements Styling */
        .elements-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }

 .elements-grid > div {
            background: #f9f9f9;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

  /* Tables */
        table {
            width: 100%;
            border-collapse: collapse;
            margin-bottom: 20px;
        }

table {
            border: 2px solid #6c757d;
        }

 th, td {
            border: 1px solid #6c757d;
            padding: 10px;
            text-align: left;
        }

 /* Social Icons */
        .social-icons a {
            margin: 0 10px;
            color: #6c757d;
            text-decoration: none;
            font-size: 1.5rem;
            transition: color 0.3s;
        }

  .social-icons a:hover {
            color: #9b59b6;
        }

 /* Responsive Design */
        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
                padding-top: 10px;
            }

  li {
                padding-bottom: 10px;
            }

 .elements-grid {
                grid-template-columns: auto;
            }
        }

   /* Footer */
        footer {
            background: rgba(44, 62, 80, 0.9);
            color: #fff;
            text-align: center;
            padding: 1rem 0;
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <nav class="container">
            <h1>Computer Science X Pro</h1>
            <ul>
                <li><a href="#intro">Intro</a></li>
                <li><a href="#work">Work</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
                <li><a href="#elements">Elements</a></li>
            </ul>
        </nav>
    </header>
    <!-- Intro Section -->
    <section id="intro" class="container">
        <h1>Intro</h1>
        <p>¿Estás listo para desbloquear tu máximo potencial y cambiar tu estado mental? En esta página web, te invitamos a explorar un mundo de posibilidades y a descubrir nuevas formas de pensar y sentir. A través de técnicas de meditación, ejercicios de respiración y consejos de bienestar, podrás calmar tu mente y encontrar la paz interior que necesitas. Así que, ¡prepárate para experimentar un cambio transformador y alcanzar un estado de claridad mental que te permita vivir al máximo! <strong>X-plora tus límites y descubre un nuevo tú</strong></p>
    </section>
    <!-- Work Section -->
    <section id="work" class="container">
        <h1>Work</h1>
        <ul>
            <li>X-plora tus posibilidades</li>
            <li>Transforma tu mente</li>
            <li>Descubre tu potencial</li>
            <li>Cambia tu perspectiva</li>
            <li>Empieza tu viaje mental</li>
        </ul>
    </section>
    <!-- About Section -->
    <section id="about" class="container">
        <h1>About</h1>
        <div class="elements-grid">
            <div>
                <h2>Nuestra misión: Transformar mentes y vidas</h2>
                <p>En Computer Science X Pro, creemos que la mente es un poderoso instrumento que puede ser entrenado y fortalecido. Nuestra misión es proporcionar herramientas y recursos para ayudar a las personas a alcanzar un estado de claridad mental y bienestar emocional.</p>
            </div>
            <div>
                <h2>Acerca de nosotros: Un equipo apasionado por el bienestar mental</h2>
                <p>Somos un equipo de apasionados del bienestar mental que se han reunido para crear un espacio donde las personas puedan encontrar apoyo y recursos para mejorar su salud mental.</p>
            </div>
            <div>
                <h2>Nuestra historia: Un viaje hacia la claridad mental</h2>
                <p>Nuestra historia comenzó con la idea de que la mente es capaz de cambiar y crecer. Desde entonces, hemos trabajado para crear un espacio que fomente la exploración y el crecimiento personal.</p>
            </div>
        </div>
        <h2>Valores</h2>
        <ul>
            <li>Nuestros valores: Compasión, empatía y autenticidad</li>
            <li>Creemos en la importancia de la auto-reflexión y la introspección para alcanzar un estado de claridad mental.</li>
            <li>Nuestro objetivo es proporcionar recursos y herramientas que sean accesibles y útiles para todos.</li>
        </ul>
    </section>
    <!-- Contact Section -->
    <section id="contact" class="container">
        <h1>Contact</h1>
        <p><strong>Número de jefe:</strong> 5538810312</p>
        <form>
            <label for="name">Name</label>
            <input type="text" id="name" placeholder="Jane Doe" required>
            <label for="email">Email</label>
            <input type="email" id="email" placeholder="ximmetop234@gmail.com" required>
            <label for="category">Category</label>
            <select id="category">
                <option value="">-</option>
                <option value="low">Low</option>
                <option value="high">High</option>
            </select>
            <label>
                <input type="checkbox"> Email me a copy
            </label>
            <label>
                <input type="checkbox"> Not a robot
            </label>
            <label for="message">Message</label>
            <textarea id="message" placeholder="Enter your message" rows="5"></textarea>
 <button type="submit">Send Message</button>
        </form>
        <div class="social-icons">
            <a href="https://twitter.com">Twitter</a>
            <a href="https://facebook.com">Facebook</a>
            <a href="https://instagram.com">Instagram</a>
            <a href="https://github.com">GitHub</a>
        </div>
    </section>
    <!-- Elements Section -->
    <section id="elements" class="container">
        <h1>Elements</h1>
        <div class="elements-grid">
            <!-- Elementos -->
            <div>
                <h2>Elementos</h2>
                <ul>
                    <li><strong>Meditación</strong>: Técnicas de meditación guiada para calmar la mente y reducir el estrés.</li>
                    <li><strong>Ejercicios de respiración</strong>: Ejercicios de respiración profunda para reducir la ansiedad y mejorar la concentración.</li>
                    <li><strong>Visualizaciones</strong>: Visualizaciones guiadas para mejorar la motivación y la confianza en uno mismo.</li>
                    <li><strong>Afiliaciones</strong>: Un espacio para conectar con otros que comparten tus intereses y objetivos.</li>
                    <li><strong>Recursos</strong>: Acceso a recursos y herramientas para mejorar la salud mental y el bienestar.</li>
                </ul>
            </div>
            <!-- Categorías -->
            <div>
                <h2>Categorías</h2>
                <ul>
                    <li><strong>Bienestar emocional</strong>: Recursos y herramientas para mejorar la salud emocional y reducir el estrés.</li>
                    <li><strong>Desarrollo personal</strong>: Recursos y herramientas para mejorar la motivación y la confianza en uno mismo.</li>
                    <li><strong>Mente y cuerpo</strong>: Recursos y herramientas para mejorar la conexión entre la mente y el cuerpo.</li>
                </ul>
            </div>
            <!-- Herramientas -->
            <div>
                <h2>Herramientas</h2>
                <ul>
                    <li><strong>Diario de gratitud</strong>: Un diario en línea para registrar las cosas que te hacen sentir agradecido.</li>
                    <li><strong>Temporizador de meditación</strong>: Un temporizador para ayudarte a mantener la concentración durante la meditación.</li>
                    <li><strong>Guías de respiración</strong>: Guías de respiración para ayudarte a mejorar la técnica.</li>
                </ul>
            </div>
            <!-- Text -->
            <div>
                <h2>Text</h2>
                <p>This is <b>bold</b> and this is <strong>strong</strong>. This is <i>italic</i> and this is <em>emphasized</em>. This is <sup>superscript</sup> text and this is <sub>subscript</sub> text. This is <u>underlined</u> and this is code: <code>for (;;) { ... }</code>. Finally, <a href="#">this is a link</a>.</p>
            </div>
            <!-- Headings -->
            <div>
                <h2>Heading Level 2</h2>
                <h3>Heading Level 3</h3>
<h4>Heading Level 4</h4>
                <h5>Heading Level 5</h5>
                <h6>Heading Level 6</h6>
            </div>
            <!-- Blockquote -->
            <div>
                <h2>Blockquote</h2>
                <blockquote>Fringilla nisl. Donec accumsan interdum nisi, quis adipiscing accumsan adipiscing eu felis iaculis volutpat ac adipiscing accumsan faucibus. Vestibulum anteipsum primis in faucibus lorem ipsum dolor sit amet.</blockquote>
            </div>
            <!-- Preformatted -->
            <div>
                <h2>Preformatted</h2>
                <pre>
i = 0;

while (!deck.isInOrder()) {
    print 'Iteration ' + i;
    deck.shuffle();
    i++;
}

print 'It took ' + i + ' iterations to sort the deck.';
                </pre>
            </div>
            <!-- Lists -->
            <div>
                <h2>Lists</h2>
                <h3>Unordered</h3>
                <ul>
                    <li>Dolor pulvinar etiam.</li>
                    <li>Sagittist adipiscing.</li>
                    <li>Felis enim feugiat.</li>
                </ul>
                <h3>Alternate</h3>
                <ul>
                    <li>Dolor pulvinar etiam.</li>
                    <li>Sagittist adipiscing.</li>
                    <li>Felis enim feugiat.</li>
                </ul>
                <h3>Ordered</h3>
                <ol>
                    <li>Dolor pulvinar etiam.</li>
                    <li>Etiam vel felis viverra.</li>
                    <li>Felis enim feugiat.</li>
                    <li>Dolor pulvinar etiam.</li>
                    <li>Etiam vel felis lorem.</li>
                    <li>Felis enim et feugiat.</li>
                </ol>
            </div>
            <!-- Icons -->
            <div>
                <h2>Icons</h2>
                <div class="social-icons">
                    <a href="https://twitter.com">Twitter</a>
                    <a href="https://facebook.com">Facebook</a>
                    <a href="https://instagram.com">Instagram</a>
                    <a href="https://github.com">GitHub</a>
                </div>
            </div>
            <!-- Actions -->
            <div>
                <h2>Actions</h2>
                <a href="#intro" class="button">Intro</a>
                <a href="#work" class="button">Work</a>
                <a href="#about" class="button">About</a>
                <a href="#contact" class="button">Contact</a>
                <a href="#elements" class="button">Elements</a>
            </div>
            <!-- Tables -->
            <div>
                <h2>Table</h2>
                <h3>Default</h3>
                <table>
                    <thead>
                        <tr>
                            <th>Name</th>
                            <th>Description</th>
                            <th>Price</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>Item One</td>
                            <td>Ante turpis integer aliquet porttitor.</td>
                            <td>29.99</td>
                        </tr>
                        <tr>
                            <td>Item Two</td>
                            <td>Vis ac commodo adipiscing arcu aliquet.</td>
                            <td>19.99</td>
                        </tr>
                        <tr>
                            <td>Item Three</td>
                            <td>Morbi faucibus arcu accumsan lorem.</td>
                            <td>29.99</td>
                        </tr>
                        <tr>
                            <td>Item Four</td>
                            <td>Vitae integer tempus condimentum.</td>
                            <td>19.99</td>
                        </tr>
                        <tr>
                            <td>Item Five</td>
                            <td>Ante turpis integer aliquet porttitor.</td>
                            <td>29.99</td>
                        </tr>
                        <tr>
                            <td colspan="2"></td>
                            <td>100.00</td>
                        </tr>
                    </tbody>
                </table>
                <h3>Alternate</h3>
                <table>
                    <thead>
                        <tr>
                            <th>Name</th>
                            <th>Description</th>
                            <th>Price</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>Item One</td>
                            <td>Ante turpis integer aliquet porttitor.</td>
                            <td>29.99</td>
                        </tr>
                        <tr>
                            <td>Item Two</td>
                            <td>Vis ac commodo adipiscing arcu aliquet.</td>
                            <td>19.99</td>
                        </tr>
                        <tr>
                            <td>Item Three</td>
                            <td>Morbi faucibus arcu accumsan lorem.</td>
                            <td>29.99</td>
                        </tr>
                        <tr>
                            <td>Item Four</td>
                            <td>Vitae integer tempus condimentum.</td>
                            <td>19.99</td>
                        </tr>
                        <tr>
                            <td>Item Five</td>
                            <td>Ante turpis integer aliquet porttitor.</td>
                            <td>29.99</td>
                        </tr>
                        <tr>
                            <td colspan="2"></td>
                            <td>100.00</td>
                        </tr>
                    </tbody>
                </table>
            </div>
            <!-- Buttons -->
            <div>
                <h2>Buttons</h2>
                <a href="#intro" class="button">Intro</a>
                <a href="#work" class="button">Work</a>
  <a href="#about" class="button">About</a>
                <a href="#contact" class="button">Contact</a>
                <a href="#elements" class="button">Elements</a>
                <a href="#" class="button disabled">Disabled</a>
            </div>
        </div>
    </section>
    <!-- Footer -->
    <footer>
        <p>© Computer Science X Pro. Design: <a href="https://html5up.net">HTML5 UP</a>. Released under the <a href="https://creativecommons.org/licenses/by/3.0/">Creative Commons License</a>.</p>
    </footer>
</body>
</html>
