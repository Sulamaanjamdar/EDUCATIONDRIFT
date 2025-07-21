# EDUCATIONDRIFT
Exploring the subtle and significant shifts shaping learning, institutions, and policies worldwide.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Education Drift</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Inter Font -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc; /* Light Slate 50 */
            color: #1e293b; /* Slate 800 */
        }
        /* Custom scrollbar for chat messages */
        .chat-messages::-webkit-scrollbar {
            width: 8px;
        }
        .chat-messages::-webkit-scrollbar-track {
            background: #f1f1f1;
            border-radius: 10px;
        }
        .chat-messages::-webkit-scrollbar-thumb {
            background: #888;
            border-radius: 10px;
        }
        .chat-messages::-webkit-scrollbar-thumb:hover {
            background: #555;
        }
        /* Style for star ratings */
        .rating input[type="radio"] {
            display: none;
        }
        .rating label {
            font-size: 1.5rem;
            color: #ccc;
            cursor: pointer;
            transition: color 0.2s;
        }
        .rating label:hover,
        .rating label:hover ~ label,
        .rating input[type="radio"]:checked ~ label {
            color: #ffc107; /* Gold color for stars */
        }
        .rating {
            direction: rtl; /* Right-to-left to make stars fill from right */
            display: inline-block;
        }
        .rating label:first-child {
            margin-left: 0;
        }
    </style>
</head>
<body class="antialiased">
    <!-- Navigation Bar -->
    <nav class="bg-white shadow-md py-4 px-6 md:px-12 flex items-center justify-between rounded-b-lg">
        <div class="flex items-center">
            <span class="text-2xl font-bold text-blue-600">EducationDrift</span>
        </div>
        <div class="hidden md:flex space-x-6">
            <a href="#home" class="text-gray-700 hover:text-blue-600 font-medium transition duration-300">Home</a>
            <a href="#about" class="text-gray-700 hover:text-blue-600 font-medium transition duration-300">About Drift</a>
            <a href="#motivation" class="text-gray-700 hover:text-blue-600 font-medium transition duration-300">Motivation</a>
            <a href="#articles" class="text-gray-700 hover:text-blue-600 font-medium transition duration-300">Articles</a>
            <a href="#feedback" class="text-gray-700 hover:text-blue-600 font-medium transition duration-300">Feedback</a>
            <a href="#chat" class="text-gray-700 hover:text-blue-600 font-medium transition duration-300">Support Chat</a>
            <a href="#contact" class="text-gray-700 hover:text-blue-600 font-medium transition duration-300">Contact</a>
        </div>
        <button class="md:hidden text-gray-700 focus:outline-none">
            <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path>
            </svg>
        </button>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="relative bg-gradient-to-r from-blue-500 to-indigo-600 text-white py-20 md:py-32 flex flex-col items-center justify-center rounded-lg m-4 shadow-lg overflow-hidden">
        <!-- Replaced placeholder with user's image -->
        <img src="http://googleusercontent.com/file_content/10" alt="Person looking at a city skyline, representing future and aspiration" class="absolute inset-0 w-full h-full object-cover opacity-20 z-0">
        <div class="text-center px-4 max-w-4xl z-10">
            <h1 class="text-4xl md:text-6xl font-extrabold leading-tight mb-6">
                Navigating the Currents of <span class="text-yellow-300">Education Drift</span>
            </h1>
            <p class="text-lg md:text-xl mb-8 opacity-90">
                Exploring the subtle and significant shifts shaping learning, institutions, and policies worldwide.
            </p>
            <a href="#about" class="inline-block bg-white text-blue-700 hover:bg-gray-100 font-bold py-3 px-8 rounded-full shadow-lg transition duration-300 transform hover:scale-105">
                Learn More
            </a>
        </div>
    </section>

    <!-- About Drift Section -->
    <section id="about" class="py-16 px-6 md:px-12 bg-white m-4 rounded-lg shadow-lg">
        <div class="max-w-6xl mx-auto">
            <h2 class="text-3xl md:text-4xl font-bold text-center text-blue-700 mb-12">What is Education Drift?</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Card 1: Academic Drift -->
                <div class="bg-gray-50 p-6 rounded-xl shadow-md border border-gray-200 flex flex-col items-center text-center">
                    <img src="https://placehold.co/100x100/A78BFA/ffffff?text=University" alt="University icon" class="mb-4 rounded-full">
                    <h3 class="text-xl font-semibold text-blue-600 mb-3">Academic Drift</h3>
                    <p class="text-gray-700">
                        The tendency for non-university institutions to adopt the characteristics and curricula of traditional universities, often driven by prestige and research focus.
                    </p>
                </div>
                <!-- Card 2: Curriculum Drift -->
                <div class="bg-gray-50 p-6 rounded-xl shadow-md border border-gray-200 flex flex-col items-center text-center">
                    <img src="https://placehold.co/100x100/34D399/ffffff?text=Curriculum" alt="Curriculum icon" class="mb-4 rounded-full">
                    <h3 class="text-xl font-semibold text-blue-600 mb-3">Curriculum Drift</h3>
                    <p class="text-gray-700">
                        When the actual delivered curriculum diverges from its intended design, leading to misalignment and potential gaps in learning outcomes.
                    </p>
                </div>
                <!-- Card 3: Policy Drift -->
                <div class="bg-gray-50 p-6 rounded-xl shadow-md border border-gray-200 flex flex-col items-center text-center">
                    <img src="https://placehold.co/100x100/FBBF24/ffffff?text=Policy" alt="Policy icon" class="mb-4 rounded-full">
                    <h3 class="text-xl font-semibold text-blue-600 mb-3">Policy Drift</h3>
                    <p class="text-gray-700">
                        The gradual, often subtle, change in the impact or effect of educational policies over time, influenced by external factors and evolving contexts.
                    </p>
                </div>
                <!-- Card 4: Student Engagement Drift -->
                <div class="bg-gray-50 p-6 rounded-xl shadow-md border border-gray-200 flex flex-col items-center text-center">
                    <img src="https://placehold.co/100x100/EF4444/ffffff?text=Student" alt="Student icon" class="mb-4 rounded-full">
                    <h3 class="text-xl font-semibold text-blue-600 mb-3">Student Engagement Drift</h3>
                    <p class="text-gray-700">
                        Shifts in student attention and involvement, exploring why focus might waver and how to foster deeper cognitive and emotional engagement.
                    </p>
                </div>
                <!-- Card 5: Future of Education -->
                <div class="bg-gray-50 p-6 rounded-xl shadow-md border border-gray-200 flex flex-col items-center text-center">
                    <img src="https://placehold.co/100x100/3B82F6/ffffff?text=Future" alt="Future icon" class="mb-4 rounded-full">
                    <h3 class="text-xl font-semibold text-blue-600 mb-3">Future of Education</h3>
                    <p class="text-gray-700">
                        Analyzing how these drifts shape the future of learning, adapting to new technologies, societal needs, and global challenges.
                    </p>
                </div>
                <!-- Card 6: Research & Insights -->
                <div class="bg-gray-50 p-6 rounded-xl shadow-md border border-gray-200 flex flex-col items-center text-center">
                    <img src="https://placehold.co/100x100/6B7280/ffffff?text=Research" alt="Research icon" class="mb-4 rounded-full">
                    <h3 class="text-xl font-semibold text-blue-600 mb-3">Research & Insights</h3>
                    <p class="text-gray-700">
                        Providing data-driven analysis and expert commentary on the various forms of education drift and their implications.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Motivational Insights Section -->
    <section id="motivation" class="py-16 px-6 md:px-12 bg-gradient-to-br from-purple-600 to-pink-500 text-white m-4 rounded-lg shadow-lg">
        <div class="max-w-6xl mx-auto text-center">
            <h2 class="text-3xl md:text-4xl font-bold mb-8">Inspiring the Journey of Learning</h2>
            <p class="text-lg mb-12 opacity-90">
                Beyond the shifts, find inspiration to embrace lifelong learning and personal growth.
            </p>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="bg-white p-6 rounded-xl shadow-md text-center text-gray-800">
                    <!-- Replaced placeholder with user's image -->
                    <img src="http://googleusercontent.com/file_content/4" alt="Person at a podium, representing growth and public speaking" class="w-full h-40 object-cover rounded-lg mb-4">
                    <h3 class="text-xl font-semibold mb-2">Embrace Growth</h3>
                    <p class="text-gray-700">
                        Learning is a continuous journey. Every challenge is an opportunity to grow and adapt.
                    </p>
                </div>
                <div class="bg-white p-6 rounded-xl shadow-md text-center text-gray-800">
                    <!-- Replaced placeholder with user's image -->
                    <img src="http://googleusercontent.com/file_content/7" alt="Person standing next to an Innovation Ignite banner" class="w-full h-40 object-cover rounded-lg mb-4">
                    <h3 class="text-xl font-semibold mb-2">Innovate & Create</h3>
                    <p class="text-gray-700">
                        The future of education is shaped by those who dare to think differently and innovate.
                    </p>
                </div>
                <div class="bg-white p-6 rounded-xl shadow-md text-center text-gray-800">
                    <!-- Replaced placeholder with user's image -->
                    <img src="http://googleusercontent.com/file_content/2" alt="Person receiving an award, symbolizing achievement and resilience" class="w-full h-40 object-cover rounded-lg mb-4">
                    <h3 class="text-xl font-semibold mb-2">Cultivate Resilience</h3>
                    <p class="text-gray-700">
                        Navigate changes with strength and determination, turning obstacles into stepping stones.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Student Feedback Form Section -->
    <section id="feedback" class="py-16 px-6 md:px-12 bg-white m-4 rounded-lg shadow-lg">
        <div class="max-w-4xl mx-auto text-center">
            <h2 class="text-3xl md:text-4xl font-bold text-blue-700 mb-8">Student Feedback Form</h2>
            <p class="text-gray-700 mb-8">
                Your valuable feedback helps us improve teaching and learning experiences. Please provide your details and rate your teacher on the following skills:
            </p>
            <form class="space-y-6">
                <div>
                    <label for="student-name" class="block text-left text-gray-700 text-sm font-medium mb-2">Your Name (Optional)</label>
                    <input type="text" id="student-name" name="student_name" placeholder="Enter your name" class="w-full p-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500">
                </div>
                <div>
                    <label for="school-name" class="block text-left text-gray-700 text-sm font-medium mb-2">School Name</label>
                    <input type="text" id="school-name" name="school_name" placeholder="e.g., Central High School" class="w-full p-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500" required>
                </div>
                <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                    <div>
                        <label for="class-name" class="block text-left text-gray-700 text-sm font-medium mb-2">Class</label>
                        <input type="text" id="class-name" name="class_name" placeholder="e.g., 10th Grade" class="w-full p-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500" required>
                    </div>
                    <div>
                        <label for="section-name" class="block text-left text-gray-700 text-sm font-medium mb-2">Section</label>
                        <input type="text" id="section-name" name="section_name" placeholder="e.g., A, B, C" class="w-full p-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500" required>
                    </div>
                </div>
                <div>
                    <label for="course-subject" class="block text-left text-gray-700 text-sm font-medium mb-2">Course/Subject</label>
                    <input type="text" id="course-subject" name="course_subject" placeholder="e.g., Mathematics, History" class="w-full p-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500" required>
                </div>

                <!-- Skill Area Ratings -->
                <div class="overflow-x-auto">
                    <table class="min-w-full bg-white border border-gray-200 rounded-lg shadow-sm">
                        <thead>
                            <tr class="bg-gray-100 text-left text-gray-600 text-sm uppercase tracking-wider">
                                <th class="py-3 px-4 border-b">Skill Area</th>
                                <th class="py-3 px-4 border-b text-center">Rating</th>
                            </tr>
                        </thead>
                        <tbody>
                            <!-- Skill: Set Induction / Introduction -->
                            <tr class="hover:bg-gray-50">
                                <td class="py-3 px-4 border-b text-gray-800">Set Induction / Introduction</td>
                                <td class="py-3 px-4 border-b text-center">
                                    <div class="rating flex justify-center items-center">
                                        <input type="radio" id="si-star5" name="set_induction" value="5" required><label for="si-star5" title="5 stars">★</label>
                                        <input type="radio" id="si-star4" name="set_induction" value="4"><label for="si-star4" title="4 stars">★</label>
                                        <input type="radio" id="si-star3" name="set_induction" value="3"><label for="si-star3" title="3 stars">★</label>
                                        <input type="radio" id="si-star2" name="set_induction" value="2"><label for="si-star2" title="2 stars">★</label>
                                        <input type="radio" id="si-star1" name="si-star1" value="1"><label for="si-star1" title="1 star">★</label>
                                    </div>
                                </td>
                            </tr>
                            <!-- Skill: Clarity of Concept -->
                            <tr class="hover:bg-gray-50">
                                <td class="py-3 px-4 border-b text-gray-800">Clarity of Concept</td>
                                <td class="py-3 px-4 border-b text-center">
                                    <div class="rating flex justify-center items-center">
                                        <input type="radio" id="cc-star5" name="clarity_concept" value="5" required><label for="cc-star5" title="5 stars">★</label>
                                        <input type="radio" id="cc-star4" name="clarity_concept" value="4"><label for="cc-star4" title="4 stars">★</label>
                                        <input type="radio" id="cc-star3" name="clarity_concept" value="3"><label for="cc-star3" title="3 stars">★</label>
                                        <input type="radio" id="cc-star2" name="clarity_concept" value="2"><label for="cc-star2" title="2 stars">★</label>
                                        <input type="radio" id="cc-star1" name="clarity_concept" value="1"><label for="cc-star1" title="1 star">★</label>
                                    </div>
                                </td>
                            </tr>
                            <!-- Skill: Use of Teaching Aids -->
                            <tr class="hover:bg-gray-50">
                                <td class="py-3 px-4 border-b text-gray-800">Use of Teaching Aids</td>
                                <td class="py-3 px-4 border-b text-center">
                                    <div class="rating flex justify-center items-center">
                                        <input type="radio" id="ta-star5" name="teaching_aids" value="5" required><label for="ta-star5" title="5 stars">★</label>
                                        <input type="radio" id="ta-star4" name="teaching_aids" value="4"><label for="ta-star4" title="4 stars">★</label>
                                        <input type="radio" id="ta-star3" name="teaching_aids" value="3"><label for="ta-star3" title="3 stars">★</label>
                                        <input type="radio" id="ta-star2" name="teaching_aids" value="2"><label for="ta-star2" title="2 stars">★</label>
                                        <input type="radio" id="ta-star1" name="teaching_aids" value="1"><label for="ta-star1" title="1 star">★</label>
                                    </div>
                                </td>
                            </tr>
                            <!-- Skill: Communication & Voice Clarity -->
                            <tr class="hover:bg-gray-50">
                                <td class="py-3 px-4 border-b text-gray-800">Communication & Voice Clarity</td>
                                <td class="py-3 px-4 border-b text-center">
                                    <div class="rating flex justify-center items-center">
                                        <input type="radio" id="cvc-star5" name="comm_voice_clarity" value="5" required><label for="cvc-star5" title="5 stars">★</label>
                                        <input type="radio" id="cvc-star4" name="comm_voice_clarity" value="4"><label for="cvc-star4" title="4 stars">★</label>
                                        <input type="radio" id="cvc-star3" name="comm_voice_clarity" value="3"><label for="cvc-star3" title="3 stars">★</label>
                                        <input type="radio" id="cvc-star2" name="comm_voice_clarity" value="2"><label for="cvc-star2" title="2 stars">★</label>
                                        <input type="radio" id="cvc-star1" name="comm_voice_clarity" value="1"><label for="cvc-star1" title="1 star">★</label>
                                    </div>
                                </td>
                            </tr>
                            <!-- Skill: Questioning Skill -->
                            <tr class="hover:bg-gray-50">
                                <td class="py-3 px-4 border-b text-gray-800">Questioning Skill</td>
                                <td class="py-3 px-4 border-b text-center">
                                    <div class="rating flex justify-center items-center">
                                        <input type="radio" id="qs-star5" name="questioning_skill" value="5" required><label for="qs-star5" title="5 stars">★</label>
                                        <input type="radio" id="qs-star4" name="questioning_skill" value="4"><label for="qs-star4" title="4 stars">★</label>
                                        <input type="radio" id="qs-star3" name="questioning_skill" value="3"><label for="qs-star3" title="3 stars">★</label>
                                        <input type="radio" id="qs-star2" name="questioning_skill" value="2"><label for="qs-star2" title="2 stars">★</label>
                                        <input type="radio" id="qs-star1" name="questioning_skill" value="1"><label for="qs-star1" title="1 star">★</label>
                                    </div>
                                </td>
                            </tr>
                            <!-- Skill: Time Management -->
                            <tr class="hover:bg-gray-50">
                                <td class="py-3 px-4 border-b text-gray-800">Time Management</td>
                                <td class="py-3 px-4 border-b text-center">
                                    <div class="rating flex justify-center items-center">
                                        <input type="radio" id="tm-star5" name="time_management" value="5" required><label for="tm-star5" title="5 stars">★</label>
                                        <input type="radio" id="tm-star4" name="time_management" value="4"><label for="tm-star4" title="4 stars">★</label>
                                        <input type="radio" id="tm-star3" name="time_management" value="3"><label for="tm-star3" title="3 stars">★</label>
                                        <input type="radio" id="tm-star2" name="time_management" value="2"><label for="tm-star2" title="2 stars">★</label>
                                        <input type="radio" id="tm-star1" name="time_management" value="1"><label for="tm-star1" title="1 star">★</label>
                                    </div>
                                </td>
                            </tr>
                            <!-- Skill: Board Work / Visuals -->
                            <tr class="hover:bg-gray-50">
                                <td class="py-3 px-4 border-b text-gray-800">Board Work / Visuals</td>
                                <td class="py-3 px-4 border-b text-center">
                                    <div class="rating flex justify-center items-center">
                                        <input type="radio" id="bw-star5" name="board_work_visuals" value="5" required><label for="bw-star5" title="5 stars">★</label>
                                        <input type="radio" id="bw-star4" name="board_work_visuals" value="4"><label for="bw-star4" title="4 stars">★</label>
                                        <input type="radio" id="bw-star3" name="board_work_visuals" value="3"><label for="bw-star3" title="3 stars">★</label>
                                        <input type="radio" id="bw-star2" name="board_work_visuals" value="2"><label for="bw-star2" title="2 stars">★</label>
                                        <input type="radio" id="bw-star1" name="board_work_visuals" value="1"><label for="bw-star1" title="1 star">★</label>
                                    </div>
                                </td>
                            </tr>
                            <!-- Skill: Conclusion / Closure -->
                            <tr class="hover:bg-gray-50">
                                <td class="py-3 px-4 border-b text-gray-800">Conclusion / Closure</td>
                                <td class="py-3 px-4 border-b text-center">
                                    <div class="rating flex justify-center items-center">
                                        <input type="radio" id="cc-star5-2" name="conclusion_closure" value="5" required><label for="cc-star5-2" title="5 stars">★</label>
                                        <input type="radio" id="cc-star4-2" name="conclusion_closure" value="4"><label for="cc-star4-2" title="4 stars">★</label>
                                        <input type="radio" id="cc-star3-2" name="conclusion_closure" value="3"><label for="cc-star3-2" title="3 stars">★</label>
                                        <input type="radio" id="cc-star2-2" name="conclusion_closure" value="2"><label for="cc-star2-2" title="2 stars">★</label>
                                        <input type="radio" id="cc-star1-2" name="conclusion_closure" value="1"><label for="cc-star1-2" title="1 star">★</label>
                                    </div>
                                </td>
                            </tr>
                        </tbody>
                    </table>
                </div>

                <!-- Additional Comments -->
                <div>
                    <label for="additional-comments" class="block text-left text-gray-700 text-sm font-medium mb-2 mt-6">Additional Comments (Optional)</label>
                    <textarea id="additional-comments" name="additional_comments" placeholder="Any other thoughts or suggestions?" rows="4" class="w-full p-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500"></textarea>
                </div>

                <button type="submit" class="bg-green-600 text-white hover:bg-green-700 font-bold py-3 px-8 rounded-full shadow-lg transition duration-300 transform hover:scale-105">
                    Submit Feedback
                </button>
            </form>
        </div>
    </section>

    <!-- Student Support Chat Section -->
    <section id="chat" class="py-16 px-6 md:px-12 bg-gray-50 m-4 rounded-lg shadow-lg">
        <div class="max-w-2xl mx-auto bg-white rounded-xl shadow-md overflow-hidden">
            <div class="bg-blue-600 text-white py-4 px-6 text-center rounded-t-xl">
                <h2 class="text-2xl font-bold">Student Support Chat</h2>
                <p class="text-sm opacity-90">Ask me anything about education!</p>
            </div>
            <div id="chat-messages" class="chat-messages p-6 h-96 overflow-y-auto flex flex-col space-y-4">
                <!-- Chat messages will be appended here -->
                <div class="flex justify-start">
                    <div class="bg-gray-200 text-gray-800 p-3 rounded-lg max-w-xs shadow">
                        Hi there! How can I assist you with your education-related queries today?
                    </div>
                </div>
            </div>
            <div class="p-4 border-t border-gray-200 flex">
                <input type="text" id="chat-input" placeholder="Type your message..." class="flex-grow p-3 border border-gray-300 rounded-l-lg focus:outline-none focus:ring-2 focus:ring-blue-500">
                <button id="send-button" class="bg-blue-600 text-white px-6 py-3 rounded-r-lg hover:bg-blue-700 transition duration-300 flex items-center justify-center">
                    <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path>
                    </svg>
                </button>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-16 px-6 md:px-12 bg-white m-4 rounded-lg shadow-lg">
        <div class="max-w-3xl mx-auto text-center">
            <h2 class="text-3xl md:text-4xl font-bold text-blue-700 mb-8">Get in Touch</h2>
            <p class="text-gray-700 mb-8">
                Have questions, insights, or want to collaborate? Reach out to us!
            </p>
            <form class="space-y-6">
                <div>
                    <input type="text" placeholder="Your Name" class="w-full p-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500">
                </div>
                <div>
                    <input type="email" placeholder="Your Email" class="w-full p-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500">
                </div>
                <div>
                    <textarea placeholder="Your Message" rows="5" class="w-full p-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500"></textarea>
                </div>
                <button type="submit" class="bg-blue-600 text-white hover:bg-blue-700 font-bold py-3 px-8 rounded-full shadow-lg transition duration-300 transform hover:scale-105">
                    Send Message
                </button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-8 px-6 md:px-12 text-center rounded-t-lg mt-4">
        <p>&copy; 2025 EducationDrift. All rights reserved.</p>
        <div class="flex justify-center space-x-4 mt-4">
            <a href="#" class="text-gray-400 hover:text-white transition duration-300">Privacy Policy</a>
            <a href="#" class="text-gray-400 hover:text-white transition duration-300">Terms of Service</a>
        </div>
    </footer>

    <script>
        const chatMessages = document.getElementById('chat-messages');
        const chatInput = document.getElementById('chat-input');
        const sendButton = document.getElementById('send-button');

        // Function to add a message to the chat display
        function addMessage(sender, message) {
            const messageDiv = document.createElement('div');
            if (sender === 'user') {
                messageDiv.className = 'flex justify-end';
                messageDiv.innerHTML = `
                    <div class="bg-blue-500 text-white p-3 rounded-lg max-w-xs shadow">
                        ${message}
                    </div>
                `;
            } else {
                messageDiv.className = 'flex justify-start';
                messageDiv.innerHTML = `
                    <div class="bg-gray-200 text-gray-800 p-3 rounded-lg max-w-xs shadow">
                        ${message}
                    </div>
                `;
            }
            chatMessages.appendChild(messageDiv);
            chatMessages.scrollTop = chatMessages.scrollHeight; // Scroll to bottom
        }

        // Function to simulate AI response using Gemini API
        async function getAiResponse(userMessage) {
            addMessage('ai', 'Typing...'); // Show typing indicator

            let chatHistory = [];
            chatHistory.push({ role: "user", parts: [{ text: userMessage }] });

            const payload = { contents: chatHistory };
            const apiKey = ""; // Canvas will automatically provide the API key
            const apiUrl = `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.0-flash:generateContent?key=${apiKey}`;

            try {
                const response = await fetch(apiUrl, {
                    method: 'POST',
                    headers: { 'Content-Type': 'application/json' },
                    body: JSON.stringify(payload)
                });
                const result = await response.json();

                // Remove typing indicator
                chatMessages.lastChild.remove();

                if (result.candidates && result.candidates.length > 0 &&
                    result.candidates[0].content && result.candidates[0].content.parts &&
                    result.candidates[0].content.parts.length > 0) {
                    const text = result.candidates[0].content.parts[0].text;
                    addMessage('ai', text);
                } else {
                    addMessage('ai', 'Sorry, I could not generate a response. Please try again.');
                    console.error('Unexpected API response structure:', result);
                }
            } catch (error) {
                // Remove typing indicator
                chatMessages.lastChild.remove();
                addMessage('ai', 'There was an error connecting to the AI. Please try again later.');
                console.error('Error fetching AI response:', error);
            }
        }

        // Event listener for send button click
        sendButton.addEventListener('click', () => {
            const userMessage = chatInput.value.trim();
            if (userMessage) {
                addMessage('user', userMessage);
                getAiResponse(userMessage);
                chatInput.value = ''; // Clear input field
            }
        });

        // Event listener for Enter key press in input field
        chatInput.addEventListener('keypress', (e) => {
            if (e.key === 'Enter') {
                sendButton.click();
            }
        });
    </script>
</body>
</html>
