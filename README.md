<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Startup Template</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <style>
        /* Custom CSS for the background image */
        .home-section {
            background-image: url('https://giffiles.alphacoders.com/174/1744.gif'); /* Replace with your image URL */
            background-size: cover; /* Ensures the image covers the entire section */
            background-position: center; /* Centers the image */
            background-repeat: no-repeat; /* Prevents the image from repeating */
        }

        /* Add some custom styles for the buttons */
        .btn {
            transition: background-color 0.3s ease;
        }

        /* Popup styles */
        .popup {
            display: none;
            position: fixed;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            background-color: rgba(0, 0, 0, 0.8);
            color: white;
            padding: 20px;
            border-radius: 10px;
            z-index: 1000;
            text-align: center;
        }

        .popup.active {
            display: block;
        }
    </style>
</head>
<body class="bg-gray-900"> <!-- Changed body background to dark gray -->

    <!-- Header Section with Dark Background -->
    <header class="bg-black-800 text-white p-4"> <!-- Changed to dark gray -->
        <div class="container mx-auto flex justify-between items-center">
            <h1 class="text-2xl font-bold">Welcome</h1>
            <nav>
                <ul class="flex space-x-4">
                    <a href="#home" class="bg-gray-700 text-white px-6 py-2 rounded-full font-semibold hover:bg-gray-600">Home</a>
                    <a href="#services" class="bg-gray-700 text-white px-6 py-2 rounded-full font-semibold hover:bg-gray-600">Services</a>
                    <a href="#Emu-apk" class="bg-gray-700 text-white px-6 py-2 rounded-full font-semibold hover:bg-gray-600">Emulator</a>
                    <a href="#contact" class="bg-gray-700 text-white px-6 py-2 rounded-full font-semibold hover:bg-gray-600">Contact</a>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Home Section with Background Image -->
    <section id="home" class="home-section text-white py-20">
        <div class="container mx-auto text-center">
            <h2 class="text-6xl font-bold mb-4">BASHI X L2H CHEAT</h2>
            <p class="mb-8">FREE FIRE SG SEVER BEST PANEL</p>
        </div>
    </section>

    <!-- Services Section with Dark Background -->
    <section id="services" class="bg-gray-800 text-white py-12"> <!-- Changed to dark gray -->
        <div class="container mx-auto">
            <h2 class="text-5xl font-bold text-center mb-8">Our Services</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="bg-gray-700 p-6 rounded-lg shadow-lg"> <!-- Changed to dark gray -->
                    <h3 class="text-3xl font-bold mb-1">Free Panel</h3>
                    <p class="mb-4">Enjoin Now Free Panel</p>
                    <div class="space-y-2">
                        <p class="text-lg font-semibold">Downlowd Exe</p>
                        <button id="downloadExeButton" class="w-full bg-gray-600 text-white px-4 py-2 rounded-full font-semibold hover:bg-blue-500">Download Exe</button>
                        <p class="text-lg font-semibold">Show User</p>
                        <button id="userButton" class="w-full bg-gray-600 text-white px-4 py-2 rounded-full font-semibold hover:bg-blue-500">User</button>
                        <p class="text-lg font-semibold">Show Password</p>
                        <button id="passwordButton" class="w-full bg-gray-600 text-white px-4 py-2 rounded-full font-semibold hover:bg-blue-500">Password</button>
                    </div>
                </div>
                <div class="bg-gray-700 p-6 rounded-lg shadow-lg"> <!-- Changed to dark gray -->
                    <h3 class="text-3xl font-bold mb-1">Paid Panel</h3>
                    <p class="mb-4">Enjoin Now Paid Panel</p>
                    <div class="space-y-2">
                        <p class="text-lg font-semibold">1 Week</p>
                        <button id="oneWeekButton" class="w-full bg-gray-600 text-white px-4 py-2 rounded-full font-semibold hover:bg-blue-500 mt-2">But Now - 1$</button>
                        <p class="text-lg font-semibold">1 Month</p>
                        <button id="oneMonthButton" class="w-full bg-gray-600 text-white px-4 py-2 rounded-full font-semibold hover:bg-blue-500 mt-2">But Now - 3$</button>
                        <p class="text-lg font-semibold">6 Month</p>
                        <button id="6MonthButton" class="w-full bg-gray-600 text-white px-4 py-2 rounded-full font-semibold hover:bg-blue-500 mt-2">But Now - 10$</button>
                    </div>
                </div>
                <div class="bg-gray-700 p-6 rounded-lg shadow-lg"> <!-- Changed to dark gray -->
                    <h3 class="text-3xl font-bold mb-1">PC Optimize</h3>
                    <p class="mb-4">Enjoin Now Free Optimize</p>
                    <!-- Added 1 Week option with 1$ button -->
                    <div class="space-y-2">
                        <p class="text-lg font-semibold">Optimize Reg</p>
                        <button id="optimiz1" class="w-full bg-gray-600 text-white px-4 py-2 rounded-full font-semibold hover:bg-blue-500 mt-2">Downlowd Now</button>
                        <p class="text-lg font-semibold">Optimize Pack 1</p>
                        <button id="optimiz2" class="w-full bg-gray-600 text-white px-4 py-2 rounded-full font-semibold hover:bg-blue-500 mt-2">Downlowd Now</button>
                        <p class="text-lg font-semibold">Optimize pack 2</p>
                        <button id="optimiz3" class="w-full bg-gray-600 text-white px-4 py-2 rounded-full font-semibold hover:bg-blue-500 mt-2">Downlowd Now</button>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Emulator and apk -->
    <section id="Emu-apk" class="bg-black-800 text-white py-20"> <!-- Changed to dark gray -->
        <div class="container mx-auto text-center">
            <h2 class="text-4xl font-bold mb-4">SAFE EMULATOR & N32 | P64 FREE FIRE APK</h2>
            <p class="mb-8">Enjoin Now free Resources</p>
            <div class="bg-gray-700 p-6 rounded-lg shadow-lg"> <!-- Changed to dark gray -->
               <div class="space-y-2">
                    <p class="text-2xl font-bold font-semibold">BS 5.10 Emulator</p>
                    <button id="emu1" class="w-full bg-gray-600 text-white px-4 py-2 rounded-full font-semibold hover:bg-blue-500 mt-2">Downlowd Now</button>
                    <p class="text-2xl font-bold font-semibold">BS 5.12 Emulator</p>
                    <button id="emu2" class="w-full bg-gray-600 text-white px-4 py-2 rounded-full font-semibold hover:bg-blue-500 mt-2">Downlowd Now</button>
                    <p class="text-2xl font-bold font-semibold">Free Fire APK</p>
                    <button id="freefireapk" class="w-full bg-gray-600 text-white px-4 py-2 rounded-full font-semibold hover:bg-blue-500 mt-2">Downlowd Now</button>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section with Dark Background -->
    <section id="contact" class="bg-gray-800 text-white py-20"> <!-- Changed to dark gray -->
        <div class="container mx-auto text-center">
            <h2 class="text-4xl font-bold mb-4">Contact Us</h2>
            <p class="mb-8">Get in touch with us for any inquiries or support</p>
            <button id="discordBtn" class="bg-gray-700 text-white px-6 py-2 rounded-full font-semibold hover:bg-gray-600">Discord</button>
            <button id="youtubeBtn" class="bg-gray-700 text-white px-6 py-2 rounded-full font-semibold hover:bg-gray-600">Youtube</button>
            <button id="whatsappBtn" class="bg-gray-700 text-white px-6 py-2 rounded-full font-semibold hover:bg-gray-600">Whatsapp</button>
        </div>
    </section>

    <!-- Footer Section with Dark Background -->
    <footer class="bg-black-800 text-white p-4"> <!-- Changed to dark gray -->
        <div class="container mx-auto text-center">
            <p>&copy; 2025 Bashi x Cheat. All rights reserved.</p>
        </div>
    </footer>

    <!-- Popup for Ads -->
    <div id="popup" class="popup">
        <p>Please watch 15s this ads</p>
    </div>

    <!-- JavaScript to handle button clicks -->
    <script>
        // Function to handle button clicks
        function handleButtonClick(event, firstUrl, secondUrl) {
            const button = event.target;
            if (!button.dataset.clicked) {
                // First click: Open the first URL in a new tab
                window.open(firstUrl, '_blank');
                button.dataset.clicked = true; // Mark as clicked
                button.textContent += " (Click again to proceed)"; // Optional: Add a hint for the user
            } else {
                // Second click: Open the second URL in a new tab
                window.open(secondUrl, '_blank');
            }
        }

        // Function to disable all buttons
        function disableAllButtons() {
            const buttons = document.querySelectorAll('button');
            buttons.forEach(button => {
                button.disabled = true;
            });
        }

        // Function to enable all buttons
        function enableAllButtons() {
            const buttons = document.querySelectorAll('button');
            buttons.forEach(button => {
                button.disabled = false;
            });
        }

        // Add event listeners to the buttons
        document.getElementById('discordBtn').addEventListener('click', (event) => {
            handleButtonClick(
                event,
                'https://www.effectiveratecpm.com/jhrez3idy?key=5bdf724ac54b86ead5439350f65640ed', // First URL
                'https://discord.gg/68hbtBevYj' // Second URL
            );
        });

        document.getElementById('youtubeBtn').addEventListener('click', (event) => {
            handleButtonClick(
                event,
                'https://www.effectiveratecpm.com/ve0qkszad?key=82b4fcc2c5ba8ca17f97600aff01fa95', // First URL
                'https://www.youtube.com/@Bashi_x_Cheat' // Second URL
            );
        });

        document.getElementById('whatsappBtn').addEventListener('click', (event) => {
            handleButtonClick(
                event,
                'https://www.effectiveratecpm.com/er15rqgtwk?key=1e85e8f1f150e390606565dd50e483f2', // First URL
                'https://chat.whatsapp.com/Krq4kJhXziODgCjqnXVHoo' // Second URL
            );
        });

        // Function to handle the User button click with a 15-second countdown
        document.getElementById('userButton').addEventListener('click', function () {
            const popup = document.getElementById('popup');
            popup.classList.add('active');

            let countdown1 = 2;

                 const countdownInterval1 = setInterval(() => {
                if (countdown1 > 0) {
                countdown1--;
                } else {
                clearInterval(countdownInterval1);
                window.open('https://www.effectiveratecpm.com/t64gig090c?key=d0bc54c20ba719744ae94f59b835b5a0', '_blank');
                
                const countdownInterval = setInterval(() => {
                if (countdown > 0) {
                    button.textContent = `Wait ${countdown}s`;
                    countdown--;
                } else {
                    clearInterval(countdownInterval);
                    button.textContent = 'User = bashix'; // Display the username
                    enableAllButtons();
                    popup.classList.remove('active');
                }
            }, 1000); // Update every 1 second
            }
            }, 1000);
            const button = this;
            let countdown = 15;

            disableAllButtons(); 
        });

        // Function to handle the Password button click with a 15-second countdown
        document.getElementById('passwordButton').addEventListener('click', function () {
            const popup = document.getElementById('popup');
            popup.classList.add('active');

            let countdown1 = 2;

                 const countdownInterval1 = setInterval(() => {
                if (countdown1 > 0) {
                countdown1--;
                } else {
                clearInterval(countdownInterval1);
                window.open('https://www.effectiveratecpm.com/idpjijqcj?key=c4681cbb9f9b2e13e9e74a9879e3aae5', '_blank');

                const countdownInterval = setInterval(() => {
                if (countdown > 0) {
                    button.textContent = `Wait ${countdown}s`;
                    countdown--;
                } else {
                    clearInterval(countdownInterval);
                    button.textContent = 'Password = 12';
                    enableAllButtons();
                    popup.classList.remove('active');
                }
            }, 1000); 
            }
            }, 1000);
            const button = this;
            let countdown = 15; 

            disableAllButtons();
        });

        // Function to handle the Download Exe button click with a 15-second countdown
        document.getElementById('downloadExeButton').addEventListener('click', function () {
            const popup = document.getElementById('popup');
            popup.classList.add('active');

            let countdown1 = 2;

                 const countdownInterval1 = setInterval(() => {
                if (countdown1 > 0) {
                countdown1--;
                } else {
                clearInterval(countdownInterval1);
                window.open('https://www.effectiveratecpm.com/sn99vt3t?key=c2d9525763342f9a839dd714cb802ab9', '_blank');

                const countdownInterval = setInterval(() => {
                if (countdown > 0) {
                    button.textContent = `Wait ${countdown}s`;
                    countdown--;
                } else {
                    clearInterval(countdownInterval);
                    button.textContent = 'Download Exe';
                    window.open('https://www.bashix.com', '_blank');
                    enableAllButtons();
                    popup.classList.remove('active');
                }
            }, 1000);
            }
            }, 1000);
            
            const button = this;
            let countdown = 15;

            disableAllButtons();   
        });

        // Function to handle the button click
        document.getElementById('oneWeekButton').addEventListener('click', function () {
            indow.open('https://www.effectiveratecpm.com/upusabpatt?key=2f4e30d841985006a25af6dd35452750', '_blank');
            window.open('https://discord.gg/68hbtBevYj', '_blank');
        });
        document.getElementById('6MonthButton').addEventListener('click', function () {
            indow.open('https://www.effectiveratecpm.com/knm76embn?key=d1c163c94fa8969a5086839d98c34587', '_blank');
            window.open('https://discord.gg/68hbtBevYj', '_blank');
        });
        document.getElementById('oneMonthButton').addEventListener('click', function () {
            indow.open('https://www.effectiveratecpm.com/mygtiafaf?key=09bbc7c815dfa4b6786e7b1ed60d93f7', '_blank');
            window.open('https://discord.gg/68hbtBevYj', '_blank');
        });

        // emulator and apk
        document.getElementById('emu1').addEventListener('click', function () {
            const popup = document.getElementById('popup');
            popup.classList.add('active');

            let countdown1 = 2;

                 const countdownInterval1 = setInterval(() => {
                if (countdown1 > 0) {
                countdown1--;
                } else {
                clearInterval(countdownInterval1);
                window.open('https://www.effectiveratecpm.com/qba0wkpp?key=0c214cf2de4c7aea24cd3704c2e8ffaf', '_blank');

                const countdownInterval = setInterval(() => {
                if (countdown > 0) {
                    button.textContent = `Wait ${countdown}s`;
                    countdown--;
                } else {
                    clearInterval(countdownInterval);
                    button.textContent = 'Download Exe';
                    window.open('https://www.mediafire.com/file/5ky866pgzn0tw7v/Bluestack+5-10-230-1003.exe/file', '_blank');
                    enableAllButtons();
                    popup.classList.remove('active');
                }
            }, 1000);
            }
            }, 1000);
            
            const button = this;
            let countdown = 15;

            disableAllButtons();    
        });

        // Function to handle the Password button click with a 15-second countdown
        document.getElementById('emu2').addEventListener('click', function () {
            const popup = document.getElementById('popup');
            popup.classList.add('active');

            let countdown1 = 2;

                 const countdownInterval1 = setInterval(() => {
                if (countdown1 > 0) {
                countdown1--;
                } else {
                clearInterval(countdownInterval1);
                window.open('https://www.effectiveratecpm.com/x8ac62ahsx?key=ce8458615b5b88f96e013b95a9d5dca7', '_blank');

                const countdownInterval = setInterval(() => {
                if (countdown > 0) {
                    button.textContent = `Wait ${countdown}s`;
                    countdown--;
                } else {
                    clearInterval(countdownInterval);
                    button.textContent = 'Download Exe';
                    window.open('https://www.mediafire.com/file/76dsulbey1onfgo/bluestacks-app-player-5-12.exe/file', '_blank');
                    enableAllButtons();
                    popup.classList.remove('active');
                }
            }, 1000);
            }
            }, 1000);
            
            const button = this;
            let countdown = 15;

            disableAllButtons();   
        });

        // Function to handle the Download Exe button click with a 15-second countdown
        document.getElementById('freefireapk').addEventListener('click', function () {
            const popup = document.getElementById('popup');
            popup.classList.add('active');

            let countdown1 = 2;

                 const countdownInterval1 = setInterval(() => {
                if (countdown1 > 0) {
                countdown1--;
                } else {
                clearInterval(countdownInterval1);
                window.open('https://www.effectiveratecpm.com/vmivj7yp?key=29bd35e3ceeda84464477e333a250a42', '_blank');

                const countdownInterval = setInterval(() => {
                if (countdown > 0) {
                    button.textContent = `Wait ${countdown}s`;
                    countdown--;
                } else {
                    clearInterval(countdownInterval);
                    button.textContent = 'Download Exe';
                    window.open('https://www.mediafire.com/file/zgj6kzbtakjh1ir/SHAN+x+CHEAT+FREE+FIRE.xapk/file', '_blank');
                    enableAllButtons();
                    popup.classList.remove('active');
                }
            }, 1000);
            }
            }, 1000);
            
            const button = this;
            let countdown = 15;

            disableAllButtons();   
        });

        // optimiz pack
        document.getElementById('optimiz1').addEventListener('click', function () {
            const popup = document.getElementById('popup');
            popup.classList.add('active');

            let countdown1 = 2;

                 const countdownInterval1 = setInterval(() => {
                if (countdown1 > 0) {
                countdown1--;
                } else {
                clearInterval(countdownInterval1);
                window.open('https://www.effectiveratecpm.com/er15rqgtwk?key=1e85e8f1f150e390606565dd50e483f2', '_blank');

                const countdownInterval = setInterval(() => {
                if (countdown > 0) {
                    button.textContent = `Wait ${countdown}s`;
                    countdown--;
                } else {
                    clearInterval(countdownInterval);
                    button.textContent = 'Download Exe';
                    window.open('https://www.bashix.com', '_blank');
                    enableAllButtons();
                    popup.classList.remove('active');
                }
            }, 1000);
            }
            }, 1000);
            
            const button = this;
            let countdown = 15;

            disableAllButtons();    
        });

        document.getElementById('optimiz2').addEventListener('click', function () {
            const popup = document.getElementById('popup');
            popup.classList.add('active');

            let countdown1 = 2;

                 const countdownInterval1 = setInterval(() => {
                if (countdown1 > 0) {
                countdown1--;
                } else {
                clearInterval(countdownInterval1);
                window.open('https://www.effectiveratecpm.com/ve0qkszad?key=82b4fcc2c5ba8ca17f97600aff01fa95', '_blank');

                const countdownInterval = setInterval(() => {
                if (countdown > 0) {
                    button.textContent = `Wait ${countdown}s`;
                    countdown--;
                } else {
                    clearInterval(countdownInterval);
                    button.textContent = 'Download Exe';
                    window.open('https://www.bashix.com', '_blank');
                    enableAllButtons();
                    popup.classList.remove('active');
                }
            }, 1000);
            }
            }, 1000);
            
            const button = this;
            let countdown = 15;

            disableAllButtons();   
        });

        document.getElementById('optimiz3').addEventListener('click', function () {
            const popup = document.getElementById('popup');
            popup.classList.add('active');

            let countdown1 = 2;

                 const countdownInterval1 = setInterval(() => {
                if (countdown1 > 0) {
                countdown1--;
                } else {
                clearInterval(countdownInterval1);
                window.open('https://www.effectiveratecpm.com/jhrez3idy?key=5bdf724ac54b86ead5439350f65640ed', '_blank');

                const countdownInterval = setInterval(() => {
                if (countdown > 0) {
                    button.textContent = `Wait ${countdown}s`;
                    countdown--;
                } else {
                    clearInterval(countdownInterval);
                    button.textContent = 'Download Exe';
                    window.open('https://www.bashix.com', '_blank');
                    enableAllButtons();
                    popup.classList.remove('active');
                }
            }, 1000);
            }
            }, 1000);
            
            const button = this;
            let countdown = 15;

            disableAllButtons();   
        });
    </script>

</body>
</html>
