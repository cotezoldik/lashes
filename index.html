<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lash Master Pro</title>
    <!-- React & ReactDOM from CDN -->
    <script crossorigin src="https://unpkg.com/react@18/umd/react.production.min.js"></script>
    <script crossorigin src="https://unpkg.com/react-dom@18/umd/react-dom.production.min.js"></script>
    <!-- Babel for JSX transformation -->
    <script src="https://unpkg.com/@babel/standalone/babel.min.js"></script>
    <!-- Tailwind CSS from CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Custom font for Inter */
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800;900&display=swap');
        body {
            font-family: 'Inter', sans-serif;
        }
    </style>
</head>
<body>
    <div id="root"></div>

    <script type="text/babel">
        // ADVERTENCIA CRÍTICA:
        // Las llamadas a la API de Gemini (para sugerencias de pestañas, análisis de cliente y preguntas a la IA)
        // MUY PROBABLEMENTE NO FUNCIONARÁN al ejecutar este archivo directamente desde tu máquina local
        // (es decir, abriendo el archivo con "file://"). Esto se debe a las políticas de seguridad del navegador (CORS).
        // Los navegadores impiden que el código local haga solicitudes a servidores externos.
        // La aplicación se cargará, pero estas funciones de IA fallarán y mostrarán errores en la consola.
        //
        // Las imágenes AHORA SON ESTÁTICAS (placehold.co) y NO USAN LA IA.
        // Si las imágenes estáticas no cargan (ves "IMAGEN NO CARGADA"), el problema es de tu navegador, red o firewall,
        // NO del código de la aplicación. Por favor, limpia la caché del navegador o prueba otra red.

        // Main App Component
        function App() {
          const [currentPage, setCurrentPage] = React.useState('home'); // State to manage current page view

          // Tailwind CSS classes for consistent styling
          const navButtonClass = "px-4 py-2 rounded-lg font-semibold transition-colors duration-200";
          const activeNavButtonClass = "bg-purple-600 text-white shadow-lg";
          const inactiveNavButtonClass = "bg-gray-200 text-gray-800 hover:bg-gray-300";

          // Render content based on the current page
          const renderPage = () => {
            switch (currentPage) {
              case 'lashTypes':
                return <LashTypes />;
              case 'learningModules':
                return <LearningModules />;
              case 'about':
                return <About />;
              default:
                return <Home />;
            }
          };

          return (
            <div className="min-h-screen bg-gradient-to-br from-purple-100 to-pink-100 font-inter text-gray-800 flex flex-col">
              {/* Header Section */}
              <header className="bg-white shadow-md p-4 flex flex-col sm:flex-row items-center justify-between sticky top-0 z-10 rounded-b-xl">
                <h1 className="text-3xl font-extrabold text-purple-700 mb-4 sm:mb-0">
                  Lash Master Pro
                </h1>
                {/* Navigation */}
                <nav className="flex flex-wrap justify-center gap-3">
                  <button
                    onClick={() => setCurrentPage('home')}
                    className={`${navButtonClass} ${currentPage === 'home' ? activeNavButtonClass : inactiveNavButtonClass}`}
                  >
                    Inicio
                  </button>
                  <button
                    onClick={() => setCurrentPage('lashTypes')}
                    className={`${navButtonClass} ${currentPage === 'lashTypes' ? activeNavButtonClass : inactiveNavButtonClass}`}
                  >
                    Tipos de Pestañas
                  </button>
                  <button
                    onClick={() => setCurrentPage('learningModules')}
                    className={`${navButtonClass} ${currentPage === 'learningModules' ? activeNavButtonClass : inactiveNavButtonClass}`}
                  >
                    Módulos de Aprendizaje
                  </button>
                  <button
                    onClick={() => setCurrentPage('about')}
                    className={`${navButtonClass} ${currentPage === 'about' ? activeNavButtonClass : inactiveNavButtonClass}`}
                  >
                    Acerca de
                  </button>
                </nav>
              </header>

              {/* Main Content Area */}
              <main className="flex-grow p-6 sm:p-8">
                <div className="max-w-4xl mx-auto bg-white p-6 sm:p-8 rounded-2xl shadow-xl">
                  {renderPage()}
                </div>
              </main>

              {/* Footer Section */}
              <footer className="bg-purple-800 text-white p-4 text-center mt-8 rounded-t-xl">
                <p>&copy; 2024 Lash Master Pro. Todos los derechos reservados.</p>
              </footer>
            </div>
          );
        }

        // Home Page Component
        function Home() {
          // Static image URL - NO AI GENERATION FOR IMAGES TO ENSURE STABILITY
          // Changed color to a distinct green for better visibility and confirmation
          const homeImageUrl = "https://placehold.co/600x400/28a745/FFFFFF?text=Esteticista+Aplicando+Pestañas";

          return (
            <div className="text-center py-8">
              <h2 className="text-4xl font-bold text-purple-700 mb-6">¡Bienvenida a Lash Master Pro!</h2>
              <p className="text-lg leading-relaxed mb-6">
                Tu guía completa para dominar el arte de las extensiones de pestañas. Explora nuestros módulos de aprendizaje,
                descubre los diferentes tipos de pestañas y mejora tus habilidades.
              </p>
              {/* Centered Static Image */}
              <div className="flex justify-center mb-6">
                <img
                  src={homeImageUrl}
                  alt="[Image of Esteticista Aplicando Pestañas]"
                  className="rounded-xl shadow-md w-full max-w-lg h-64 object-cover mx-auto"
                  // Fallback if placehold.co itself fails (very rare) - distinct red
                  onError={(e) => { e.target.onerror = null; e.target.src = 'https://placehold.co/400x250/FF0000/FFFFFF?text=IMAGEN+NO+CARGADA'; }}
                />
              </div>
              <p className="text-md mt-6 text-gray-600">
                ¡Comienza tu viaje hoy mismo! Navega por las secciones de arriba para empezar.
              </p>
            </div>
          );
        }

        // Lash Types Page Component
        function LashTypes() {
          // Static image URLs for each lash type - NO AI GENERATION FOR IMAGES TO ENSURE STABILITY
          // Changed color to a distinct green for better visibility and confirmation
          const classicImage = "https://placehold.co/300x200/28a745/FFFFFF?text=Pestañas+Clásicas";
          const volumeImage = "https://placehold.co/300x200/28a745/FFFFFF?text=Pestañas+Volumen";
          const hybridImage = "https://placehold.co/300x200/28a745/FFFFFF?text=Pestañas+Híbridas";
          const megaVolumeImage = "https://placehold.co/300x200/28a745/FFFFFF?text=Pestañas+Mega+Volumen";
          const lashLiftImage = "https://placehold.co/300x200/28a745/FFFFFF?text=Levantamiento+Pestañas";

          // isLoading states are always false now as images are static
          const loadingState = false; // Consolidated loading state as it's always false for static images

          const lashTypes = [
            {
              name: "Pestañas Clásicas",
              description: "Las extensiones clásicas consisten en aplicar una extensión individual a una pestaña natural. Proporcionan un aspecto más natural, añadiendo longitud y un poco de volumen.",
              image: classicImage,
              isLoading: loadingState,
              details: [
                "Relación 1:1 (una extensión por pestaña natural)",
                "Ideal para un look natural o para quienes tienen muchas pestañas naturales",
                "Duración: 2-3 semanas con relleno"
              ]
            },
            {
              name: "Pestañas de Volumen (2D-6D)",
              description: "Las extensiones de volumen, también conocidas como pestañas rusas de volumen, implican la creación de 'abanicos' de múltiples extensiones ligeras (2-6D) que se aplican a una sola pestaña natural. Ofrecen un aspecto más denso y dramático.",
              image: volumeImage,
              isLoading: loadingState,
              details: [
                "Abanicos prefabricados o hechos a mano (2D-6D)",
                "Crean un aspecto más lleno y dramático",
                "Duración: 3-4 semanas con relleno"
              ]
            },
            {
              name: "Pestañas Híbridas",
              description: "Las pestañas híbridas son una combinación de extensiones clásicas y de volumen. Ofrecen una textura más completa que las clásicas, pero menos dramática que el volumen completo, logrando un look versátil.",
              image: hybridImage,
              isLoading: loadingState,
              details: [
                "Mezcla de técnicas clásicas y de volumen",
                "Aspecto texturizado y completo",
                "Duración: 3-4 semanas con relleno"
              ]
            },
            {
              name: "Pestañas Mega Volumen (7D+)",
              description: "El mega volumen lleva las pestañas de volumen al siguiente nivel, utilizando abanicos aún más grandes y ligeros (7D o más) para crear un efecto extremadamente denso y glamuroso.",
              image: megaVolumeImage,
              isLoading: loadingState,
              details: [
                "Abanicos muy grandes (7D o más)",
                "Para un look ultra-dramático y denso",
                "Duración: 4-5 semanas con relleno"
              ]
            },
            {
              name: "Levantamiento de Pestañas (Lash Lift)",
              description: "No es una extensión, sino un tratamiento que riza y levanta las pestañas naturales desde la raíz, haciéndolas parecer más largas y voluminosas. A menudo se combina con un tinte de pestañas.",
              image: lashLiftImage,
              isLoading: loadingState,
              details: [
                "Tratamiento semipermanente para pestañas naturales",
                "Crea un efecto de rizado y levantamiento",
                "Duración: 6-8 semanas"
              ]
            }
          ];

          const [eyeShape, setEyeShape] = React.useState('');
          const [desiredLook, setDesiredLook] = React.useState('');
          const [occasion, setOccasion] = React.useState(''); // New state for occasion
          const [lashSuggestion, setLashSuggestion] = React.useState('');
          const [loadingSuggestion, setLoadingSuggestion] = React.useState(false);

          const [clientDescription, setClientDescription] = React.useState(''); // New state for client description
          const [clientAnalysis, setClientAnalysis] = React.useState(''); // New state for AI client analysis
          const [loadingAnalysis, setLoadingAnalysis] = React.useState(false); // New state for loading analysis


          const handleSuggestLashCombination = async () => {
            if (!eyeShape || !desiredLook || !occasion) { // Added occasion to validation
              setLashSuggestion("Por favor, selecciona la forma de ojo, el aspecto deseado y la ocasión.");
              return;
            }

            setLoadingSuggestion(true);
            setLashSuggestion(''); // Clear previous suggestion

            // Prompt updated to include occasion
            const prompt = `Sugiere la mejor combinación de tipos de extensiones de pestañas (Clásicas, Volumen, Híbridas, Mega Volumen, Levantamiento de Pestañas) para una persona con forma de ojo "${eyeShape}" que busca un aspecto "${desiredLook}" para la ocasión "${occasion}". Sé conciso y menciona 2-3 opciones si es posible, explicando brevemente por qué.`;

            try {
              let chatHistory = [];
              chatHistory.push({ role: "user", parts: [{ text: prompt }] });
              const payload = { contents: chatHistory };
              const apiKey = ""; // Canvas will provide in runtime if run in supported environments.
              const apiUrl = `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.0-flash:generateContent?key=${apiKey}`;

              const response = await fetch(apiUrl, {
                method: 'POST',
                headers: { 'Content-Type': 'application/json' },
                body: JSON.stringify(payload)
              });
              const result = await response.json();

              if (result.candidates && result.candidates.length > 0 &&
                  result.candidates[0].content && result.candidates[0].content.parts &&
                  result.candidates[0].content.parts.length > 0) {
                const text = result.candidates[0].content.parts[0].text;
                setLashSuggestion(text);
              } else {
                setLashSuggestion('No se pudo generar la sugerencia. Inténtalo de nuevo.');
              }
            } catch (error) {
              console.error("Error generating lash combination:", error);
              setLashSuggestion('Error al conectar con la IA. (CORS puede ser la causa en entorno local)');
            } finally {
              setLoadingSuggestion(false);
            }
          };

          // New function to handle client description analysis
          const handleAnalyzeClient = async () => {
            if (!clientDescription.trim()) {
              setClientAnalysis("Por favor, introduce una descripción del cliente para el análisis.");
              return;
            }

            setLoadingAnalysis(true);
            setClientAnalysis(''); // Clear previous analysis

            const prompt = `Analiza la siguiente descripción de cliente para extensiones de pestañas y sugiere los tipos de pestañas más adecuados (Clásicas, Volumen, Híbridas, Mega Volumen, Levantamiento de Pestañas), explicando brevemente por qué. Ten en cuenta el tono, las preferencias mencionadas y cualquier detalle relevante: "${clientDescription}"`;

            try {
              let chatHistory = [];
              chatHistory.push({ role: "user", parts: [{ text: prompt }] });
              const payload = { contents: chatHistory };
              const apiKey = ""; // Canvas will provide in runtime.
              const apiUrl = `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.0-flash:generateContent?key=${apiKey}`;

              const response = await fetch(apiUrl, {
                method: 'POST',
                headers: { 'Content-Type': 'application/json' },
                body: JSON.stringify(payload)
              });
              const result = await response.json();

              if (result.candidates && result.candidates.length > 0 &&
                  result.candidates[0].content && result.candidates[0].content.parts &&
                  result.candidates[0].content.parts.length > 0) {
                const text = result.candidates[0].content.parts[0].text;
                setClientAnalysis(text);
              } else {
                setClientAnalysis('No se pudo analizar la descripción del cliente. Inténtalo de nuevo.');
              }
            } catch (error) {
              console.error("Error analyzing client description:", error);
              setClientAnalysis('Error al conectar con la IA. (CORS puede ser la causa en entorno local)');
            } finally {
              setLoadingAnalysis(false);
            }
          };


          return (
            <div className="py-8">
              <h2 className="text-3xl font-bold text-purple-700 mb-8 text-center">Tipos de Pestañas</h2>
              
              {/* Lash Combination Suggester */}
              <div className="bg-purple-50 rounded-xl shadow-lg p-6 mb-8 border border-purple-200">
                <h3 className="text-2xl font-semibold text-purple-700 mb-4 text-center">
                  Sugerencia Personalizada de Pestañas ✨
                </h3>
                <div className="grid grid-cols-1 md:grid-cols-3 gap-4 mb-4"> {/* Adjusted grid for 3 columns */}
                  <div>
                    <label htmlFor="eyeShape" className="block text-gray-700 text-sm font-bold mb-2">
                      Forma de Ojo:
                    </label>
                    <select
                      id="eyeShape"
                      value={eyeShape}
                      onChange={(e) => setEyeShape(e.target.value)}
                      className="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline focus:border-purple-500 transition-colors duration-200"
                    >
                      <option value="">Selecciona una forma</option>
                      <option value="Almendrada">Almendrada</option>
                      <option value="Redonda">Redonda</option>
                      <option value="Monólido">Monólido</option>
                      <option value="Encappuchados">Encappuchados</option>
                      <option value="Caídos">Caídos</option>
                      <option value="Grandes">Grandes</option>
                      <option value="Pequeños">Pequeños</option>
                      <option value="Juntos">Juntos</option>
                      <option value="Separados">Separados</option>
                    </select>
                  </div>
                  <div>
                    <label htmlFor="desiredLook" className="block text-gray-700 text-sm font-bold mb-2">
                      Aspecto Deseado:
                    </label>
                    <select
                      id="desiredLook"
                      value={desiredLook}
                      onChange={(e) => setDesiredLook(e.target.value)}
                      className="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline focus:border-purple-500 transition-colors duration-200"
                    >
                      <option value="">Selecciona un aspecto</option>
                      <option value="Natural Suave">Natural Suave</option>
                      <option value="Volumen Sutil">Volumen Sutil</option>
                      <option value="Dramático y Extenso">Dramático y Extenso</option>
                      <option value="Efecto Mojado">Efecto Mojado</option>
                      <option value="Fox Eye (Ojo de Zorro)">Fox Eye (Ojo de Zorro)</option>
                      <option value="Muñeca Abierta">Muñeca Abierta</option>
                      <option value="Kim K (Picotazos)">Kim K (Picotazos)</option>
                      <option value="Clásico Elegante">Clásico Elegante</option>
                      <option value="Volumen Ruso Completo">Volumen Ruso Completo</option>
                    </select>
                  </div>
                  {/* Occasion Select */}
                  <div>
                    <label htmlFor="occasion" className="block text-gray-700 text-sm font-bold mb-2">
                      Ocasión:
                    </label>
                    <select
                      id="occasion"
                      value={occasion}
                      onChange={(e) => setOccasion(e.target.value)}
                      className="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline focus:border-purple-500 transition-colors duration-200"
                    >
                      <option value="">Selecciona una ocasión</option>
                      <option value="Diario">Diario</option>
                      <option value="Fiesta">Fiesta</option>
                      <option value="Boda">Boda</option>
                      <option value="Evento Formal">Evento Formal</option>
                      <option value="Sesión de Fotos">Sesión de Fotos</option>
                      <option value="Vacaciones">Vacaciones</option>
                    </select>
                  </div>
                </div>
                <button
                  onClick={handleSuggestLashCombination}
                  className="w-full bg-indigo-500 text-white py-2 px-4 rounded-lg font-semibold hover:bg-indigo-600 transition-colors duration-200 shadow-md flex items-center justify-center"
                  disabled={loadingSuggestion}
                >
                  {loadingSuggestion ? (
                    <svg className="animate-spin -ml-1 mr-3 h-5 w-5 text-white" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24">
                      <circle className="opacity-25" cx="12" cy="12" r="10" stroke="currentColor" strokeWidth="4"></circle>
                      <path className="opacity-75" fill="currentColor" d="M4 12a8 8 0 018-8V0C5.373 0 0 5.373 0 12h4zm2 5.291A7.962 7.962 0 014 12H0c0 3.042 1.135 5.824 3 7.938l3-2.647z"></path>
                    </svg>
                  ) : (
                    'Sugerir Combinación de Pestañas ✨'
                  )}
                </button>
                {lashSuggestion && (
                  <div className="mt-4 p-4 bg-white rounded-lg border border-indigo-300 text-indigo-800 text-sm italic">
                    <strong>Sugerencia de la IA:</strong> {lashSuggestion}
                  </div>
                )}
              </div>

              {/* Client Analysis Section */}
              <div className="bg-purple-50 rounded-xl shadow-lg p-6 mb-8 border border-purple-200">
                <h3 className="text-2xl font-semibold text-purple-700 mb-4 text-center">
                  Análisis de Cliente con IA ✨
                </h3>
                <p className="text-gray-700 mb-4 text-center">
                  Describe a tu cliente (ej. forma de ojo, preferencias, estilo de vida) y la IA te sugerirá el estilo de pestañas ideal.
                </p>
                <textarea
                  className="w-full p-3 border rounded-lg focus:outline-none focus:ring-2 focus:ring-purple-400 mb-4 resize-y"
                  rows="4"
                  placeholder="Ej: Mi cliente tiene ojos almendrados y busca un look natural para uso diario. Es muy activa y le gusta el maquillaje mínimo."
                  value={clientDescription}
                  onChange={(e) => setClientDescription(e.target.value)}
                ></textarea>
                <button
                  onClick={handleAnalyzeClient}
                  className="w-full bg-green-500 text-white py-2 px-4 rounded-lg font-semibold hover:bg-green-600 transition-colors duration-200 shadow-md flex items-center justify-center"
                  disabled={loadingAnalysis}
                >
                  {loadingAnalysis ? (
                    <svg className="animate-spin -ml-1 mr-3 h-5 w-5 text-white" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24">
                      <circle className="opacity-25" cx="12" cy="12" r="10" stroke="currentColor" strokeWidth="4"></circle>
                      <path className="opacity-75" fill="currentColor" d="M4 12a8 8 0 018-8V0C5.373 0 0 5.373 0 12h4zm2 5.291A7.962 7.962 0 014 12H0c0 3.042 1.135 5.824 3 7.938l3-2.647z"></path>
                    </svg>
                  ) : (
                    'Analizar Cliente con IA ✨'
                  )}
                </button>
                {clientAnalysis && (
                  <div className="mt-4 p-4 bg-white rounded-lg border border-green-300 text-green-800 text-sm italic">
                    <strong>Análisis de la IA:</strong> {clientAnalysis}
                  </div>
                )}
              </div>

              <div className="grid grid-cols-1 md:grid-cols-2 gap-8">
                {lashTypes.map((type, index) => (
                  <div key={index} className="bg-white rounded-xl shadow-lg p-6 flex flex-col items-center border border-purple-200 transform hover:scale-105 transition-transform duration-300">
                    {/* Display static image */}
                    <img
                      src={type.image}
                      alt={`[Imagen de ${type.name}]`}
                      className="w-full h-48 object-cover rounded-md mb-4 shadow-md"
                      // Fallback for static images will be less frequent but still good to have
                      onError={(e) => { e.target.onerror = null; e.target.src = `https://placehold.co/300x200/FF0000/FFFFFF?text=IMAGEN+NO+CARGADA`; }}
                    />
                    <h3 className="text-2xl font-semibold text-purple-600 mb-3">{type.name}</h3>
                    <p className="text-gray-700 text-center mb-4 leading-relaxed">{type.description}</p>
                    <ul className="text-gray-600 text-left w-full list-disc list-inside">
                      {type.details.map((detail, dIndex) => (
                        <li key={dIndex}>{detail}</li>
                      ))}
                    </ul>
                  </div>
                ))}
              </div>
            </div>
          );
        }

        // LearningSection Component (Uses static images)
        function LearningSection({ moduleIndex, sectionIndex, section, generatedTips, setLoadingTips, setGeneratedTips, loadingTips }) {
          // Static image URL based on section name
          // Changed color to a distinct green for better visibility and confirmation
          const getStaticImageUrl = (sectionName) => {
            switch (sectionName) {
              case "1.1 Anatomía y Ciclo de la Pestaña":
                return "https://placehold.co/350x200/28a745/FFFFFF?text=Anatomía+del+Cil";
              case "1.2 Higiene y Seguridad":
                return "https://placehold.co/350x200/28a745/FFFFFF?text=Higiene+y+Seguridad";
              case "1.3 Herramientas y Materiales Esenciales":
                return "https://placehold.co/350x200/28a745/FFFFFF?text=Herramientas+y+Materiales";
              case "2.1 Preparación del Cliente":
                return "https://placehold.co/350x200/28a745/FFFFFF?text=Preparación+Cliente";
              case "2.2 Técnicas de Aislamiento":
                return "https://placehold.co/350x200/28a745/FFFFFF?text=Técnicas+Aislamiento";
              case "2.3 Aplicación 1:1 y Adhesión":
                return "https://placehold.co/350x200/28a745/FFFFFF?text=Aplicación+1:1";
              case "3.1 Mapeo de Pestañas":
                return "https://placehold.co/350x200/28a745/FFFFFF?text=Mapeo+Pestañas";
              case "3.2 Curvaturas y Grosores":
                return "https://placehold.co/350x200/28a745/FFFFFF?text=Curvaturas+y+Grosores";
              case "4.1 Cuidado Post-Aplicación":
                return "https://placehold.co/350x200/28a745/FFFFFF?text=Cuidado+Post-Aplicación";
              case "4.2 Rellenos y Retirada":
                return "https://placehold.co/350x200/28a745/FFFFFF?text=Rellenos+y+Retirada";
              default:
                return "https://placehold.co/350x200/28a745/FFFFFF?text=Imagen+Módulo";
            }
          };

          const generatedSectionImageUrl = getStaticImageUrl(section.name);
          const isLoadingSectionImage = false; // No loading needed as it's static

          // New states for Q&A feature
          const [question, setQuestion] = React.useState('');
          const [answer, setAnswer] = React.useState('');
          const [loadingAnswer, setLoadingAnswer] = React.useState(false);

          // Function to generate a lash tip using Gemini API (remains same)
          const generateLashTip = async (content) => {
            setLoadingTips(prev => ({ ...prev, [`${moduleIndex}-${sectionIndex}`]: true }));
            // Prompt in Spanish
            const prompt = `Dado el siguiente contenido sobre extensiones de pestañas, genera un consejo práctico para un principiante en una frase corta y concisa (máximo 20 palabras) que pueda integrarse directamente en el texto del módulo: "${content}"`;

            try {
              let chatHistory = [];
              chatHistory.push({ role: "user", parts: [{ text: prompt }] });
              const payload = { contents: chatHistory };
              const apiKey = ""; // Canvas will provide in runtime.
              const apiUrl = `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.0-flash:generateContent?key=${apiKey}`;

              const response = await fetch(apiUrl, {
                method: 'POST',
                headers: { 'Content-Type': 'application/json' },
                body: JSON.stringify(payload)
              });
              const result = await response.json();

              if (result.candidates && result.candidates.length > 0 &&
                  result.candidates[0].content && result.candidates[0].content.parts &&
                  result.candidates[0].content.parts.length > 0) {
                const text = result.candidates[0].content.parts[0].text;
                setGeneratedTips(prev => ({ ...prev, [`${moduleIndex}-${sectionIndex}`]: text }));
              } else {
                setGeneratedTips(prev => ({ ...prev, [`${moduleIndex}-${sectionIndex}`]: 'No se pudo generar el consejo. Inténtalo de nuevo.' }));
              }
            } catch (error) {
              console.error("Error generating lash tip:", error);
              setGeneratedTips(prev => ({ ...prev, [`${moduleIndex}-${sectionIndex}`]: 'Error al conectar con la IA. (CORS puede ser la causa en entorno local)' }));
            } finally {
              setLoadingTips(prev => ({ ...prev, [`${moduleIndex}-${sectionIndex}`]: false }));
            }
          };

          // New function to answer questions about the module content
          const handleAskQuestion = async () => {
            if (!question.trim()) {
              setAnswer("Por favor, escribe una pregunta para obtener una respuesta.");
              return;
            }

            setLoadingAnswer(true);
            setAnswer(''); // Clear previous answer

            // Prompt combines section content as context and user's question
            const prompt = `Basado en el siguiente contenido sobre extensiones de pestañas y técnicas, responde a la pregunta. Si la pregunta no está directamente relacionada, indica que no tienes información:
            Contenido: "${section.content}"
            Pregunta: "${question}"`;

            try {
              let chatHistory = [];
              chatHistory.push({ role: "user", parts: [{ text: prompt }] });
              const payload = { contents: chatHistory };
              const apiKey = ""; // Canvas will provide in runtime.
              const apiUrl = `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.0-flash:generateContent?key=${apiKey}`;

              const response = await fetch(apiUrl, {
                method: 'POST',
                headers: { 'Content-Type': 'application/json' },
                body: JSON.stringify(payload)
              });
              const result = await response.json();

              if (result.candidates && result.candidates.length > 0 &&
                  result.candidates[0].content && result.candidates[0].content.parts &&
                  result.candidates[0].content.parts.length > 0) {
                const text = result.candidates[0].content.parts[0].text;
                setAnswer(text);
              } else {
                setAnswer('No se pudo obtener una respuesta. Inténtalo de nuevo.');
              }
            } catch (error) {
              console.error("Error asking question to AI:", error);
              setAnswer('Error al conectar con la IA. (CORS puede ser la causa en entorno local)');
            } finally {
              setLoadingAnswer(false);
            }
          };


          return (
            <div className="bg-white rounded-lg p-5 shadow-sm border border-gray-200">
              <h4 className="text-xl font-medium text-purple-600 mb-3">{section.name}</h4>
              <p className="text-gray-700 mb-4">{section.content}</p>

              {/* Display Generated Tip directly within the section */}
              {generatedTips[`${moduleIndex}-${sectionIndex}`] && (
                <div className="mt-4 p-3 bg-purple-100 rounded-lg border border-purple-300 text-purple-800 text-sm italic">
                  <h5 className="font-semibold text-purple-700 mb-2">Consejo de la IA:</h5>
                  <p>{generatedTips[`${moduleIndex}-${sectionIndex}`]}</p>
                </div>
              )}

              {section.videoLink && (
                <p className="text-blue-600 hover:underline mb-4">
                  <a href={section.videoLink} target="_blank" rel="noopener noreferrer">
                    Ver Video (Enlace de ejemplo)
                  </a>
                </p>
              )}

              {/* Static Section Image */}
              <img
                src={generatedSectionImageUrl}
                alt={`[Imagen de ${section.name}]`}
                className="mt-4 w-full rounded-md shadow-sm object-cover h-48"
                onError={(e) => { e.target.onerror = null; e.target.src = `https://placehold.co/350x200/FF0000/FFFFFF?text=IMAGEN+NO+CARGADA`; }}
              />

              {/* Gemini API Integration: Generate Tip Button */}
              <button
                onClick={() => generateLashTip(section.content)}
                className="mt-4 w-full bg-pink-500 text-white py-2 px-4 rounded-lg font-semibold hover:bg-pink-600 transition-colors duration-200 shadow-md flex items-center justify-center"
                disabled={loadingTips[`${moduleIndex}-${sectionIndex}`]}
              >
                {loadingTips[`${moduleIndex}-${sectionIndex}`] ? (
                  <svg className="animate-spin -ml-1 mr-3 h-5 w-5 text-white" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24">
                    <circle className="opacity-25" cx="12" cy="12" r="10" stroke="currentColor" strokeWidth="4"></circle>
                    <path className="opacity-75" fill="currentColor" d="M4 12a8 8 0 018-8V0C5.373 0 0 5.373 0 12h4zm2 5.291A7.962 7.962 0 014 12H0c0 3.042 1.135 5.824 3 7.938l3-2.647z"></path>
                  </svg>
                ) : (
                  'Generar Nuevo Consejo ✨'
                )}
              </button>

              {/* New Q&A with AI Section */}
              <div className="mt-6 p-4 bg-gray-50 rounded-lg border border-gray-200">
                <h5 className="text-xl font-semibold text-gray-700 mb-3 text-center">Pregúntale a la IA sobre este Módulo ✨</h5>
                <textarea
                  className="w-full p-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-purple-300 mb-3 resize-y"
                  rows="2"
                  placeholder="Ej: ¿Cuál es la diferencia entre la fase anágena y telógena?"
                  value={question}
                  onChange={(e) => setQuestion(e.target.value)}
                ></textarea>
                <button
                  onClick={handleAskQuestion}
                  className="w-full bg-purple-500 text-white py-2 px-4 rounded-lg font-semibold hover:bg-purple-600 transition-colors duration-200 shadow-md flex items-center justify-center"
                  disabled={loadingAnswer}
                >
                  {loadingAnswer ? (
                    <svg className="animate-spin -ml-1 mr-3 h-5 w-5 text-white" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24">
                      <circle className="opacity-25" cx="12" cy="12" r="10" stroke="currentColor" strokeWidth="4"></circle>
                      <path className="opacity-75" fill="currentColor" d="M4 12a8 8 0 018-8V0C5.373 0 0 5.373 0 12h4zm2 5.291A7.962 7.962 0 014 12H0c0 3.042 1.135 5.824 3 7.938l3-2.647z"></path>
                    </svg>
                  ) : (
                    'Obtener Respuesta de la IA ✨'
                  )}
                </button>
                {answer && (
                  <div className="mt-3 p-3 bg-white rounded-lg border border-purple-200 text-purple-700 text-sm italic">
                    <strong>Respuesta de la IA:</strong> {answer}
                  </div>
                )}
              </div>
            </div>
          );
        }


        // Learning Modules Page Component
        function LearningModules() {
          const modules = [
            {
              title: "Módulo 1: Fundamentos de las Extensiones de Pestañas",
              description: "Aprende sobre la anatomía de la pestaña, higiene, seguridad y los materiales esenciales.",
              image: "https://placehold.co/300x200/93c5fd/ffffff?text=Modulo+1",
              sections: [
                {
                  name: "1.1 Anatomía y Ciclo de la Pestaña",
                  content: "Explora la estructura de la pestaña natural y su ciclo de crecimiento. Comprender esto es crucial para una aplicación segura y duradera de las extensiones.",
                  videoLink: "https://www.youtube.com/watch?v=ejemplo1" // Placeholder for video
                },
                {
                  name: "1.2 Higiene y Seguridad",
                  content: "Protocolos de limpieza, esterilización de herramientas, prevención de infecciones y alergias. La seguridad del cliente es primordial.",
                  videoLink: "https://www.youtube.com/watch?v=ejemplo2"
                },
                {
                  name: "1.3 Herramientas y Materiales Esenciales",
                  content: "Descubre los diferentes tipos de pinzas, adhesivos, parches, desmaquillantes y extensiones que necesitarás.",
                  videoLink: "https://www.youtube.com/watch?v=ejemplo3"
                }
              ]
            },
            {
              title: "Módulo 2: Técnicas de Aplicación Clásica",
              description: "Domina la técnica 1:1 para un look natural y elegante.",
              image: "https://placehold.co/300x200/bfdbfe/ffffff?text=Modulo+2",
              sections: [
                {
                  name: "2.1 Preparación del Cliente",
                  content: "Cómo limpiar y preparar las pestañas naturales, aislar las pestañas inferiores y preparar el área de trabajo.",
                  videoLink: "https://www.youtube.com/watch?v=ejemplo4"
                },
                {
                  name: "2.2 Técnicas de Aislamiento",
                  content: "La importancia del aislamiento perfecto para evitar que las extensiones se peguen entre sí.",
                  videoLink: "https://www.youtube.com/watch?v=ejemplo5"
                },
                {
                  name: "2.3 Aplicación 1:1 y Adhesión",
                  content: "Guía paso a paso para aplicar una extensión a una pestaña natural con la cantidad adecuada de adhesivo.",
                  videoLink: "https://www.youtube.com/watch?v=ejemplo6"
                }
              ]
            },
            {
              title: "Módulo 3: Diseño y Estilismo de Pestañas",
              description: "Aprende a personalizar los sets de pestañas para diferentes formas de ojos y deseos del cliente.",
              image: "https://placehold.co/300x200/dbeafe/ffffff?text=Modulo+3",
              sections: [
                {
                  name: "3.1 Mapeo de Pestañas",
                  content: "Técnicas de mapeo para crear diferentes estilos (ojo de gato, muñeca, natural) y longitudes.",
                  videoLink: "https://www.youtube.com/watch?v=ejemplo7"
                },
                {
                  name: "3.2 Curvaturas y Grosores",
                  content: "Selección de curvaturas (J, B, C, CC, D, L, M) y grosores para el efecto deseado.",
                  videoLink: "https://www.youtube.com/watch?v=ejemplo8"
                }
              ]
            },
            {
              title: "Módulo 4: Cuidado y Mantenimiento",
              description: "Instrucciones para el cuidado posterior de las extensiones y cómo realizar rellenos y retiradas seguras.",
              image: "https://placehold.co/300x200/eff6ff/ffffff?text=Modulo+4",
              sections: [
                {
                  name: "4.1 Cuidado Post-Aplicación",
                  content: "Consejos para el cliente sobre cómo cuidar sus extensiones de pestañas para prolongar su durabilidad.",
                  videoLink: "https://www.youtube.com/watch?v=ejemplo9"
                },
                {
                  name: "4.2 Rellenos y Retirada",
                  content: "Técnicas para realizar rellenos de forma efectiva y cómo retirar las extensiones de forma segura.",
                  videoLink: "https://www.youtube.com/watch?v=ejemplo10"
                }
              ]
            }
          ];

          const [expandedModule, setExpandedModule] = React.useState(null); // State to manage expanded module
          const [generatedTips, setGeneratedTips] = React.useState({}); // State to store generated tips for each section
          const [loadingTips, setLoadingTips] = React.useState({}); // State to manage loading status for each tip generation

          const toggleModule = (index) => {
            setExpandedModule(expandedModule === index ? null : index);
          };


          return (
            <div className="py-8">
              <h2 className="text-3xl font-bold text-purple-700 mb-8 text-center">Módulos de Aprendizaje</h2>
              <div className="space-y-6">
                {modules.map((module, mIndex) => (
                  <div key={mIndex} className="bg-white rounded-xl shadow-lg p-6 flex flex-col items-center border border-purple-200 overflow-hidden">
                    <button
                      className="w-full text-left p-6 flex flex-col sm:flex-row items-center justify-between bg-purple-50 hover:bg-purple-100 transition-colors duration-200"
                      onClick={() => toggleModule(mIndex)}
                    >
                      <img
                        src={module.image}
                        alt={module.title}
                        className="w-24 h-24 object-cover rounded-full mb-4 sm:mb-0 sm:mr-6 shadow-md"
                        onError={(e) => { e.target.onerror = null; e.target.src = `https://placehold.co/100x100/${Math.floor(Math.random()*16777215).toString(16)}/ffffff?text=Error`; }}
                      />
                      <div className="flex-1">
                        <h3 className="text-2xl font-semibold text-purple-700 mb-2">{module.title}</h3>
                        <p className="text-gray-600">{module.description}</p>
                      </div>
                      <span className="text-purple-600 text-2xl ml-4">
                        {expandedModule === mIndex ? '▲' : '▼'}
                      </span>
                    </button>
                    {expandedModule === mIndex && (
                      <div className="p-6 bg-purple-50 border-t border-purple-200">
                        <div className="space-y-6">
                          {module.sections.map((section, sIndex) => (
                            <LearningSection
                              key={sIndex}
                              moduleIndex={mIndex}
                              sectionIndex={sIndex}
                              section={section}
                              generatedTips={generatedTips}
                              setLoadingTips={setLoadingTips}
                              setGeneratedTips={setGeneratedTips}
                              loadingTips={loadingTips} // Pass loadingTips prop here
                            />
                          ))}
                        </div>
                      </div>
                    )}
                  </div>
                ))}
              </div>
            </div>
          );
        }

        // About Page Component
        function About() {
          return (
            <div className="py-8 text-center">
              <h2 className="text-3xl font-bold text-purple-700 mb-6">Acerca de Lash Master Pro</h2>
              <p className="text-lg leading-relaxed mb-4">
                Lash Master Pro es una plataforma dedicada a proporcionar recursos completos para aspirantes y profesionales
                de las extensiones de pestañas. Nuestro objetivo es ofrecer información de calidad, módulos de aprendizaje
                interactivos y las últimas tendencias en la industria de la belleza.
              </p>
              <p className="text-lg leading-relaxed">
                Creemos en el poder de la educación y la práctica para perfeccionar las habilidades.
                ¡Únete a nuestra comunidad y eleva tu arte de las pestañas!
              </p>
              <img
                src="https://placehold.co/500x300/a78bfa/ffffff?text=Equipo+Lash+Master"
                alt="[Image of Equipo Lash Master Pro]"
                className="mt-8 mx-auto rounded-xl shadow-md w-full max-w-lg"
                onError={(e) => { e.target.onerror = null; e.target.src = 'https://placehold.co/500x300/FF0000/FFFFFF?text=IMAGEN+NO+CARGADA'; }}
              />
            </div>
          );
        }

        ReactDOM.render(<App />, document.getElementById('root'));
    </script>
</body>
</html>
