<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Free AI Classroom Toolkit - Ana Carolina Pessoa</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            scroll-behavior: smooth;
        }
        .gradient-bg {
            background: linear-gradient(135deg, #f0f9ff 0%, #e0f2fe 100%);
        }
        .card-shadow {
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06);
        }
        .wise-card:hover {
            transform: translateY(-5px);
            transition: all 0.3s ease;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-900 leading-relaxed">

    <!-- Header / Hero Section -->
    <header class="gradient-bg border-b border-blue-100 py-16 px-6">
        <div class="max-w-4xl mx-auto text-center">
            <h1 class="text-4xl md:text-5xl font-extrabold text-blue-900 mb-4 tracking-tight">
                Free AI Classroom Toolkit
            </h1>
            <p class="text-xl md:text-2xl text-blue-700 font-medium mb-6">
                Teaching AI Critically in Communicative Language Classrooms
            </p>
            <div class="inline-block bg-white px-4 py-2 rounded-full text-sm font-semibold text-blue-600 shadow-sm border border-blue-100">
                By Ana Carolina Pessoa
            </div>
            
            <div class="mt-12 text-left bg-white p-8 rounded-2xl shadow-sm border border-slate-100 max-w-3xl mx-auto">
                <h2 class="text-xl font-bold mb-4 flex items-center">
                    <svg class="w-6 h-6 mr-2 text-blue-500" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 16h-1v-4h-1m1-4h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                    Why Free and Accessible Activities Matter
                </h2>
                <p class="text-slate-600">
                    In many contexts, including Brazil, students have unequal access to technology. Classroom activities should prioritize free tools that work across devices. AI literacy is not about mastering one platform, but about learning to question AI output, evaluate information critically, and use AI responsibly.
                </p>
            </div>
        </div>
    </header>

    <main class="max-w-5xl mx-auto px-6 py-12 space-y-20">

        <!-- The WISE Framework -->
        <section id="wise-framework">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold text-slate-800">The WISE Framework</h2>
                <p class="text-slate-500 mt-2">A simple checklist for student-AI interaction</p>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
                <!-- W -->
                <div class="wise-card bg-white p-6 rounded-xl border-t-4 border-blue-500 card-shadow">
                    <div class="text-4xl font-black text-blue-500 mb-2">W</div>
                    <h3 class="font-bold text-lg mb-2 text-slate-800 text-nowrap">Watch for Hallucinations</h3>
                    <p class="text-sm text-slate-600">AI can generate confident but incorrect information. Always verify facts.</p>
                </div>
                <!-- I -->
                <div class="wise-card bg-white p-6 rounded-xl border-t-4 border-green-500 card-shadow">
                    <div class="text-4xl font-black text-green-500 mb-2">I</div>
                    <h3 class="font-bold text-lg mb-2 text-slate-800">Inspire Creativity</h3>
                    <p class="text-sm text-slate-600">AI should support ideas, not replace student thinking or unique voices.</p>
                </div>
                <!-- S -->
                <div class="wise-card bg-white p-6 rounded-xl border-t-4 border-orange-500 card-shadow">
                    <div class="text-4xl font-black text-orange-500 mb-2">S</div>
                    <h3 class="font-bold text-lg mb-2 text-slate-800">Safety First</h3>
                    <p class="text-sm text-slate-600">Avoid sharing personal or sensitive information with any AI tool.</p>
                </div>
                <!-- E -->
                <div class="wise-card bg-white p-6 rounded-xl border-t-4 border-purple-500 card-shadow">
                    <div class="text-4xl font-black text-purple-500 mb-2">E</div>
                    <h3 class="font-bold text-lg mb-2 text-slate-800">Ethical Use</h3>
                    <p class="text-sm text-slate-600">Be transparent about when and how AI assistance was utilized in your work.</p>
                </div>
            </div>
        </section>

        <!-- Prompt Formula Section -->
        <section id="prompt-formula" class="bg-blue-900 text-white rounded-3xl p-8 md:p-12 shadow-xl">
            <div class="flex flex-col md:flex-row items-center gap-10">
                <div class="md:w-1/2">
                    <h2 class="text-3xl font-bold mb-6">A Simple Prompt Formula</h2>
                    <div class="space-y-4">
                        <div class="flex items-start gap-4">
                            <span class="bg-blue-700 px-3 py-1 rounded font-bold">ROLE</span>
                            <p class="text-blue-100 italic">"Act as an ESL writing tutor..."</p>
                        </div>
                        <div class="flex items-start gap-4">
                            <span class="bg-blue-700 px-3 py-1 rounded font-bold">TASK</span>
                            <p class="text-blue-100 italic">"Identify three grammatical errors..."</p>
                        </div>
                        <div class="flex items-start gap-4">
                            <span class="bg-blue-700 px-3 py-1 rounded font-bold text-nowrap">CONTEXT</span>
                            <p class="text-blue-100 italic">"B1 English student essay on social media..."</p>
                        </div>
                        <div class="flex items-start gap-4">
                            <span class="bg-blue-700 px-3 py-1 rounded font-bold">LIMITS</span>
                            <p class="text-blue-100 italic">"Do not rewrite the essay; give 3 suggestions only."</p>
                        </div>
                    </div>
                </div>
                <div class="md:w-1/2 bg-blue-800 p-6 rounded-2xl border border-blue-700">
                    <div class="text-center mb-4 text-blue-300 font-semibold tracking-widest text-sm uppercase">Formula Map</div>
                    <div class="flex justify-between items-center text-sm font-bold">
                        <div class="bg-white text-blue-900 p-3 rounded shadow">ROLE</div>
                        <div class="text-white">→</div>
                        <div class="bg-white text-blue-900 p-3 rounded shadow">TASK</div>
                        <div class="text-white">→</div>
                        <div class="bg-white text-blue-900 p-3 rounded shadow">CONTEXT</div>
                        <div class="text-white">→</div>
                        <div class="bg-white text-blue-900 p-3 rounded shadow">LIMITS</div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Classroom Prompts Grid -->
        <section id="example-prompts">
            <h2 class="text-3xl font-bold text-slate-800 text-center mb-10">Example Classroom Prompts</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                
                <!-- Prompt Card 1 -->
                <div class="bg-white rounded-2xl p-6 border border-slate-200 card-shadow flex flex-col">
                    <h3 class="text-xl font-bold text-blue-600 mb-2">Register Shifter</h3>
                    <p class="text-sm text-slate-500 mb-4">Analyze tone, vocabulary, and formality.</p>
                    <div class="bg-slate-50 p-4 rounded-lg border border-slate-100 font-mono text-sm mb-4 flex-grow relative">
                        "Rewrite the sentence below for three different audiences: a close friend; a university professor; a workplace manager. Sentence: 'I cannot attend the meeting.'"
                        <button onclick="copyText(this)" class="absolute top-2 right-2 p-1 text-slate-400 hover:text-blue-500">
                            <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 5H6a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2v-1M8 5a2 2 0 002 2h2a2 2 0 002-2M8 5a2 2 0 012-2h2a2 2 0 012 2m0 0h2a2 2 0 012 2v3m2 4H10m0 0l3-3m-3 3l3 3"></path></svg>
                        </button>
                    </div>
                </div>

                <!-- Prompt Card 2 -->
                <div class="bg-white rounded-2xl p-6 border border-slate-200 card-shadow flex flex-col">
                    <h3 class="text-xl font-bold text-blue-600 mb-2">The Sandwich Method</h3>
                    <p class="text-sm text-slate-500 mb-4">AI-assisted editing without replacing human voice.</p>
                    <div class="bg-slate-50 p-4 rounded-lg border border-slate-100 font-mono text-sm mb-4 flex-grow relative">
                        "Act as an ESL writing tutor. Identify three grammatical errors in my essay and explain why they are errors. Do not rewrite the essay."
                        <button onclick="copyText(this)" class="absolute top-2 right-2 p-1 text-slate-400 hover:text-blue-500">
                            <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 5H6a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2v-1M8 5a2 2 0 002 2h2a2 2 0 002-2M8 5a2 2 0 012-2h2a2 2 0 012 2m0 0h2a2 2 0 012 2v3m2 4H10m0 0l3-3m-3 3l3 3"></path></svg>
                        </button>
                    </div>
                </div>

                <!-- Prompt Card 3 -->
                <div class="bg-white rounded-2xl p-6 border border-slate-200 card-shadow flex flex-col">
                    <h3 class="text-xl font-bold text-blue-600 mb-2">Socratic Debate Partner</h3>
                    <p class="text-sm text-slate-500 mb-4">Prepare for arguments and defend ideas.</p>
                    <div class="bg-slate-50 p-4 rounded-lg border border-slate-100 font-mono text-sm mb-4 flex-grow relative">
                        "I am preparing an argument about [topic]. Act as a debate opponent. Provide three counterarguments and ask one challenging follow-up question."
                        <button onclick="copyText(this)" class="absolute top-2 right-2 p-1 text-slate-400 hover:text-blue-500">
                            <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 5H6a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2v-1M8 5a2 2 0 002 2h2a2 2 0 002-2M8 5a2 2 0 012-2h2a2 2 0 012 2m0 0h2a2 2 0 012 2v3m2 4H10m0 0l3-3m-3 3l3 3"></path></svg>
                        </button>
                    </div>
                </div>

                <!-- Prompt Card 4 -->
                <div class="bg-white rounded-2xl p-6 border border-slate-200 card-shadow flex flex-col">
                    <h3 class="text-xl font-bold text-blue-600 mb-2">Cambridge Speaking Practice</h3>
                    <p class="text-sm text-slate-500 mb-4">One-on-one simulated speaking test feedback.</p>
                    <div class="bg-slate-50 p-4 rounded-lg border border-slate-100 font-mono text-sm mb-4 flex-grow relative text-xs">
                        "Act as a Cambridge English speaking examiner. Ask me questions similar to Part 1 of a Cambridge speaking test. Ask one question at a time. After three questions, give feedback on: fluency, vocabulary range, grammatical accuracy & pronunciation clarity."
                        <button onclick="copyText(this)" class="absolute top-2 right-2 p-1 text-slate-400 hover:text-blue-500">
                            <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 5H6a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2v-1M8 5a2 2 0 002 2h2a2 2 0 002-2M8 5a2 2 0 012-2h2a2 2 0 012 2m0 0h2a2 2 0 012 2v3m2 4H10m0 0l3-3m-3 3l3 3"></path></svg>
                        </button>
                    </div>
                </div>
            </div>
        </section>

        <!-- Tool Directory -->
        <section id="tools">
            <h2 class="text-3xl font-bold text-slate-800 text-center mb-10">Free AI Tools Directory</h2>
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
                <!-- Tool 1 -->
                <div class="bg-white p-6 rounded-xl border border-slate-100 shadow-sm hover:bg-blue-50 transition-colors">
                    <h4 class="font-bold text-lg mb-1 text-blue-700">NotebookLM</h4>
                    <p class="text-sm text-slate-600">Summarizing articles and generating discussion questions from uploaded files.</p>
                </div>
                <!-- Tool 2 -->
                <div class="bg-white p-6 rounded-xl border border-slate-100 shadow-sm hover:bg-blue-50 transition-colors">
                    <h4 class="font-bold text-lg mb-1 text-blue-700">Visuwords</h4>
                    <p class="text-sm text-slate-600">A visual dictionary for exploring synonyms and word relationships.</p>
                </div>
                <!-- Tool 3 -->
                <div class="bg-white p-6 rounded-xl border border-slate-100 shadow-sm hover:bg-blue-50 transition-colors">
                    <h4 class="font-bold text-lg mb-1 text-blue-700">Hemingway App</h4>
                    <p class="text-sm text-slate-600">Highlights complex sentences and passive voice to improve writing clarity.</p>
                </div>
                <!-- Tool 4 -->
                <div class="bg-white p-6 rounded-xl border border-slate-100 shadow-sm hover:bg-blue-50 transition-colors">
                    <h4 class="font-bold text-lg mb-1 text-blue-700">ElevenLabs</h4>
                    <p class="text-sm text-slate-600">Generates audio from text for listening and pronunciation practice.</p>
                </div>
                <!-- Tool 5 -->
                <div class="bg-white p-6 rounded-xl border border-slate-100 shadow-sm hover:bg-blue-50 transition-colors">
                    <h4 class="font-bold text-lg mb-1 text-blue-700">Mureka</h4>
                    <p class="text-sm text-slate-600">AI music tool for experimenting with lyric writing and creative language.</p>
                </div>
            </div>
        </section>

        <!-- Design Template -->
        <section id="template" class="border-2 border-dashed border-blue-200 rounded-3xl p-8 bg-white">
            <h2 class="text-2xl font-bold text-slate-800 mb-6 flex items-center">
                <svg class="w-6 h-6 mr-2 text-blue-500" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M11 5H6a2 2 0 00-2 2v11a2 2 0 002 2h11a2 2 0 002-2v-5m-1.414-9.414a2 2 0 112.828 2.828L11.828 15H9v-2.828l8.586-8.586z"></path></svg>
                AI Activity Design Template
            </h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-x-8 gap-y-6 text-sm">
                <div class="p-4 rounded-lg bg-slate-50 border border-slate-100">
                    <div class="font-bold text-blue-600 mb-1">Learning Objective</div>
                    <div class="text-slate-500">What language skill is the activity developing?</div>
                </div>
                <div class="p-4 rounded-lg bg-slate-50 border border-slate-100">
                    <div class="font-bold text-blue-600 mb-1">Communicative Task</div>
                    <div class="text-slate-500">What meaningful task will they complete?</div>
                </div>
                <div class="p-4 rounded-lg bg-slate-50 border border-slate-100">
                    <div class="font-bold text-blue-600 mb-1">AI Role</div>
                    <div class="text-slate-500">What role will the AI play? (e.g. Tutor, Opponent)</div>
                </div>
                <div class="p-4 rounded-lg bg-slate-50 border border-slate-100">
                    <div class="font-bold text-blue-600 mb-1">Critical Thinking Task</div>
                    <div class="text-slate-500">What will they evaluate?</div>
                </div>
                <div class="p-4 rounded-lg bg-slate-50 border border-slate-100">
                    <div class="font-bold text-blue-600 mb-1">Prompt</div>
                    <div class="text-slate-500">Use the Formula: Role + Task + Context + Limits</div>
                </div>
                <div class="p-4 rounded-lg bg-slate-50 border border-slate-100">
                    <div class="font-bold text-blue-600 mb-1">Proof of Work</div>
                    <div class="text-slate-500">Reflection question: "What suggestion did you accept/reject?"</div>
                </div>
            </div>
        </section>

    </main>

    <!-- Footer / Reflection -->
    <footer class="bg-slate-900 text-white py-16 px-6">
        <div class="max-w-4xl mx-auto">
            <div class="flex flex-col md:flex-row justify-between items-start gap-10">
                <div class="md:w-1/2">
                    <h3 class="text-2xl font-bold mb-4">Reflection</h3>
                    <p class="text-slate-400 mb-6">
                        Are the AI suggestions useful? 
                        What did you learn? 
                        What would you change next time? 
                        Critical AI literacy is an ongoing process of reflection.
                    </p>
                    <div class="flex space-x-4">
                        <span class="bg-slate-800 text-slate-300 px-4 py-1 rounded-full text-xs">AI Literacy</span>
                        <span class="bg-slate-800 text-slate-300 px-4 py-1 rounded-full text-xs">Critical Pedagogy</span>
                        <span class="bg-slate-800 text-slate-300 px-4 py-1 rounded-full text-xs">ELT</span>
                    </div>
                </div>
                <div class="md:w-1/3 text-slate-500 text-sm">
                    <p class="mb-2 uppercase font-bold tracking-widest text-slate-400">Toolkit Credits</p>
                    <p>Authored by Ana Carolina Pessoa</p>
                    <p>Teaching AI Critically in Language Classrooms</p>
                    <p class="mt-4">&copy; 2026 AI Classroom Toolkit</p>
                </div>
            </div>
        </div>
    </footer>

    <!-- Toast Notification System (Replacement for Alert) -->
    <div id="toast" class="fixed bottom-10 right-10 bg-blue-600 text-white px-6 py-3 rounded-xl shadow-2xl opacity-0 transition-opacity pointer-events-none">
        Prompt copied to clipboard!
    </div>

    <script>
        function copyText(button) {
            const container = button.parentElement;
            const text = container.innerText.trim();
            
            // Use standard copy command for artifact environments
            const textArea = document.createElement("textarea");
            textArea.value = text;
            document.body.appendChild(textArea);
            textArea.select();
            try {
                document.execCommand('copy');
                showToast();
            } catch (err) {
                console.error('Copy failed', err);
            }
            document.body.removeChild(textArea);
        }

        function showToast() {
            const toast = document.getElementById('toast');
            toast.style.opacity = "1";
            setTimeout(() => {
                toast.style.opacity = "0";
            }, 3000);
        }
    </script>
</body>
</html>
