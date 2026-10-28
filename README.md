<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Granja El Amanecer | Tarjeta Digital</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome para los iconos -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        farm: {
                            bg: '#f3f8f2',      /* Fondo claro verdoso */
                            dark: '#2c4c3b',    /* Verde oscuro para títulos */
                            btn: '#5a8258',     /* Verde de los botones */
                            btnHover: '#466844',/* Verde oscuro para hover */
                            text: '#4a6b58'     /* Verde medio para subtítulos */
                        }
                    }
                }
            }
        }
    </script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap');
        
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #f3f8f2;
            /* Patrón sutil de fondo */
            background-image: radial-gradient(#d5e5d5 1px, transparent 1px);
            background-size: 20px 20px;
        }

        /* Estilo para los botones inspirados en la imagen */
        .btn-link {
            transition: all 0.3s ease;
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06), inset 0 2px 4px rgba(255, 255, 255, 0.2);
        }
        
        .btn-link:hover {
            transform: translateY(-4px);
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.2), 0 4px 6px -2px rgba(0, 0, 0, 0.1), inset 0 2px 4px rgba(255, 255, 255, 0.2);
        }
    </style>
</head>
<body class="min-h-screen flex items-center justify-center p-4 sm:p-8">

    <!-- Contenedor Principal (Estilo Linktree) -->
    <main class="w-full max-w-md bg-white/60 backdrop-blur-sm rounded-[2rem] p-6 sm:p-10 shadow-2xl shadow-green-900/10 border border-green-100 text-center relative overflow-hidden">
        
        <!-- Elemento decorativo superior curvo (simulando el diseño de la imagen) -->
        <div class="absolute top-0 left-0 w-full h-32 bg-gradient-to-b from-farm-btn/20 to-transparent -z-10 rounded-t-[2rem]"></div>

        <!-- Imagen de Perfil Exacta Solicitada -->
        <img src="https://img.magnific.com/foto-gratis/fotografia-vertical-gran-granero-cerca-colina-coloridos-arboles-otono_181624-40430.jpg?semt=ais_hybrid&w=740&q=80" alt="" class="w-48 h-48 rounded-full border-4 border-green-600 object-cover shadow-lg mx-auto mb-4 z-10 relative">

        <!-- Títulos -->
        <h1 class="text-3xl font-bold text-farm-dark mb-1 tracking-tight">
            Granja El Amanecer
        </h1>
        <p class="text-farm-text font-medium mb-8 text-sm sm:text-base">
            Productos Frescos y Naturales
        </p>

        <!-- Contenedor de Botones -->
        <div class="flex flex-col gap-5 w-full">
            
            <!-- Botón WhatsApp -->
            <a href="https://wa.me/50240952400" target="_blank" rel="noopener noreferrer" 
               class="btn-link relative flex items-center w-full p-4 bg-farm-btn hover:bg-farm-btnHover text-white rounded-full decoration-none overflow-hidden group">
                <div class="absolute left-6 text-2xl">
                    <i class="fa-brands fa-whatsapp"></i>
                </div>
                <span class="w-full text-center font-semibold text-[15px] sm:text-base pl-8">WhatsApp: +502 4095 2400</span>
            </a>

            <!-- Botón Instagram -->
            <a href="https://www.instagram.com/granja__amanecer?psln=MTV2ZDB5cWYxN2R6Mg==" target="_blank" rel="noopener noreferrer" 
               class="btn-link relative flex items-center w-full p-4 bg-farm-btn hover:bg-farm-btnHover text-white rounded-full decoration-none overflow-hidden group">
                <div class="absolute left-6 text-2xl">
                    <i class="fa-brands fa-instagram"></i>
                </div>
                <span class="w-full text-center font-semibold text-[15px] sm:text-base pl-8">Instagram: @granja__amanecer</span>
            </a>

            <!-- Botón Correo -->
            <a href="mailto:granjaelamanecer00@gmail.com" target="_blank" rel="noopener noreferrer" 
               class="btn-link relative flex items-center w-full p-4 bg-farm-btn hover:bg-farm-btnHover text-white rounded-full decoration-none overflow-hidden group">
                <div class="absolute left-6 text-xl">
                    <i class="fa-solid fa-envelope"></i>
                </div>
                <span class="w-full text-center font-semibold text-[13px] sm:text-[15px] pl-8">Correo: granjaelamanecer00@gmail.com</span>
            </a>

        </div>

        <!-- Footer -->
        <div class="mt-10">
            <p class="text-farm-dark font-semibold text-sm sm:text-base">
                ¡De nuestra granja a tu mesa!<br>Contáctanos
            </p>
        </div>

    </main>

</body>
</html>
