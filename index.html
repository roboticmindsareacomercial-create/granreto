import React, { useState, useEffect } from 'react';
import { Play, User, Cpu, Battery, Zap, AlertTriangle, ShieldCheck, Download, Table, Trash2, X, RefreshCw, Lock, Copy, Check, Building } from 'lucide-react';

// --- COMPONENTES DE ANIMACIÓN (SVG ARTESANALES) ---

const AnimRobot = () => (
  <svg viewBox="0 0 100 100" className="w-24 h-24 text-blue-500">
    <rect x="20" y="30" width="60" height="50" rx="10" fill="currentColor" className="text-blue-100" />
    <rect x="20" y="30" width="60" height="50" rx="10" stroke="currentColor" strokeWidth="3" fill="none" />
    <circle cx="35" cy="50" r="5" fill="currentColor"><animate attributeName="opacity" values="1;0;1" dur="3s" repeatCount="indefinite" /></circle>
    <circle cx="65" cy="50" r="5" fill="currentColor"><animate attributeName="opacity" values="1;0;1" dur="3s" repeatCount="indefinite" /></circle>
    <line x1="50" y1="30" x2="50" y2="10" stroke="currentColor" strokeWidth="3" />
    <circle cx="50" cy="10" r="3" fill="red" className="animate-ping" />
    <rect x="35" y="65" width="30" height="5" rx="2" fill="currentColor" />
  </svg>
);

const AnimButton = () => (
  <svg viewBox="0 0 100 100" className="w-24 h-24 text-yellow-500">
    <rect x="20" y="40" width="60" height="40" rx="5" fill="#e2e8f0" stroke="currentColor" strokeWidth="2" />
    <circle cx="50" cy="60" r="15" fill="currentColor" className="text-yellow-400">
      <animate attributeName="r" values="15;12;15" dur="1.5s" repeatCount="indefinite" />
      <animate attributeName="fill-opacity" values="1;0.6;1" dur="1.5s" repeatCount="indefinite" />
    </circle>
    <path d="M50 20 L50 40" stroke="currentColor" strokeWidth="4" strokeLinecap="round">
      <animate attributeName="y1" values="20;35;20" dur="1.5s" repeatCount="indefinite" />
      <animate attributeName="y2" values="40;55;40" dur="1.5s" repeatCount="indefinite" />
    </path>
  </svg>
);

const AnimGear = () => (
  <svg viewBox="0 0 100 100" className="w-24 h-24 text-green-500 animate-[spin_4s_linear_infinite]">
    <path fill="currentColor" d="M95.6,41.9l-11.2-1.9c-1-3.6-2.5-7-4.5-10.2l7.2-8.8c0.8-1,0.7-2.4-0.1-3.3l-6.2-6.2 c-0.9-0.9-2.3-1-3.3-0.1l-8.8,7.2c-3.1-2-6.6-3.5-10.2-4.5l-1.9-11.2C56.5,1.8,55.5,1,54.2,1h-8.8c-1.3,0-2.3,0.8-2.5,2.1 l-1.9,11.2c-3.6,1-7,2.5-10.2,4.5l-8.8-7.2c-1-0.8-2.4-0.7-3.3,0.1l-6.2,6.2c-0.9,0.9-1,2.3-0.1,3.3l7.2,8.8 c-2,3.1-3.5,6.6-4.5,10.2l-11.2,1.9C2.8,42.3,2,43.3,2,44.6v8.8c0,1.3,0.8,2.3,2.1,2.5l11.2,1.9c1,3.6,2.5,7,4.5,10.2l-7.2,8.8 c-0.8,1-0.7,2.4,0.1,3.3l6.2,6.2c0.9,0.9,2.3,1,3.3,0.1l8.8-7.2c3.1,2,6.6,3.5,10.2,4.5l1.9,11.2c0.2,1.3,1.2,2.1,2.5,2.1h8.8 c1.3,0,2.3-0.8,2.5-2.1l1.9-11.2c3.6-1,7-2.5,10.2-4.5l8.8,7.2c1,0.8,2.4,0.7,3.3-0.1l6.2-6.2c0.9-0.9,1-2.3,0.1-3.3 l-7.2-8.8c2-3.1,3.5-6.6,4.5-10.2l11.2-1.9c1.3-0.2,2.1-1.2,2.1-2.5v-8.8C97.7,43.1,96.9,42.1,95.6,41.9z M50,68 c-9.9,0-18-8.1-18-18s8.1-18,18-18s18,8.1,18,18S59.9,68,50,68z" className="text-green-200" opacity="0.6"/>
    <circle cx="50" cy="50" r="12" fill="none" stroke="currentColor" strokeWidth="8" />
  </svg>
);

const AnimBattery = () => (
  <svg viewBox="0 0 100 100" className="w-24 h-24 text-red-500">
    <rect x="25" y="25" width="50" height="50" rx="4" stroke="currentColor" strokeWidth="4" fill="none" />
    <rect x="40" y="15" width="20" height="10" fill="currentColor" />
    <rect x="30" y="30" width="40" height="40" fill="currentColor" className="text-green-500">
      <animate attributeName="height" values="5;40;5" dur="2s" repeatCount="indefinite" />
      <animate attributeName="y" values="65;30;65" dur="2s" repeatCount="indefinite" />
      <animate attributeName="fill" values="#ef4444;#22c55e;#ef4444" dur="2s" repeatCount="indefinite" />
    </rect>
    <path d="M45 45 L55 50 L45 55" stroke="white" strokeWidth="2" fill="none" opacity="0.8"/>
  </svg>
);

const AnimSensor = () => (
  <svg viewBox="0 0 100 100" className="w-24 h-24 text-orange-500">
    <circle cx="30" cy="50" r="10" fill="currentColor" />
    <rect x="80" y="20" width="10" height="60" fill="gray" />
    <path d="M45 40 Q55 50 45 60" fill="none" stroke="currentColor" strokeWidth="2">
      <animate attributeName="stroke-opacity" values="1;0" dur="1s" repeatCount="indefinite" />
      <animate attributeName="d" values="M45 40 Q55 50 45 60; M70 20 Q90 50 70 80" dur="1s" repeatCount="indefinite" />
    </path>
  </svg>
);

// --- CONFIGURACIÓN DE PREGUNTAS ---

const QUESTIONS = [
  {
    id: 1,
    question: "¿Qué es un robot?",
    animation: <AnimRobot />, 
    options: [
      { id: 'A', text: "Una persona que trabaja" },
      { id: 'B', text: "Una máquina que puede hacer tareas", correct: true },
      { id: 'C', text: "Una película de acción" }
    ]
  },
  {
    id: 2,
    question: "¿Para qué sirve un botón en un robot?",
    animation: <AnimButton />,
    options: [
      { id: 'A', text: "Para recibir una orden (encender/iniciar)", correct: true },
      { id: 'B', text: "Para que el robot sea más grande" },
      { id: 'C', text: "Para cambiar el color del piso" }
    ]
  },
  {
    id: 3,
    question: "¿Cuál de estos es un ejemplo de 'movimiento'?",
    animation: <AnimGear />,
    options: [
      { id: 'A', text: "Encender una luz" },
      { id: 'B', text: "Girar una rueda", correct: true },
      { id: 'C', text: "Poner una etiqueta" }
    ]
  },
  {
    id: 4,
    question: "¿Qué hace una batería en un robot?",
    animation: <AnimBattery />,
    options: [
      { id: 'A', text: "Le da energía para funcionar", correct: true },
      { id: 'B', text: "Lo hace más inteligente" },
      { id: 'C', text: "Lo vuelve invisible" }
    ]
  },
  {
    id: 5,
    question: "Si un robot choca con una pared, ¿qué debería hacer?",
    animation: <AnimSensor />,
    options: [
      { id: 'A', text: "Seguir igual sin parar" },
      { id: 'B', text: "Intentar detenerse o girar", correct: true },
      { id: 'C', text: "Apagarse para siempre" }
    ]
  }
];

// --- COMPONENTE PRINCIPAL ---

export default function RoboticMindsApp() {
  const [step, setStep] = useState('landing');
  
  // Datos del formulario
  const [formData, setFormData] = useState({
    parentName: '',
    phone: '',
    studentName: '',
    age: '',
    school: '' 
  });

  const [currentQuestion, setCurrentQuestion] = useState(0);
  const [answers, setAnswers] = useState({});
  const [score, setScore] = useState(0);
  const [database, setDatabase] = useState([]);
  const [copied, setCopied] = useState(false); 

  useEffect(() => {
    const savedData = localStorage.getItem('roboticMindsDB_v3');
    if (savedData) {
      setDatabase(JSON.parse(savedData));
    }
  }, []);

  // --- HANDLERS LÓGICOS ---

  const handleStart = () => setStep('register');

  const handleInputChange = (e) => {
    const { name, value } = e.target;
    setFormData(prev => ({ ...prev, [name]: value }));
  };

  const handleRegisterSubmit = (e) => {
    e.preventDefault();
    if (!formData.parentName || !formData.phone || !formData.studentName || !formData.age || !formData.school) {
      alert("Por favor completa TODOS los campos, incluyendo el Colegio.");
      return;
    }
    setStep('quiz');
  };

  const handleAnswerOption = (isCorrect, optionId) => {
    setAnswers(prev => ({ ...prev, [currentQuestion]: optionId }));
    if (isCorrect) setScore(prev => prev + 1);

    setTimeout(() => {
      if (currentQuestion < QUESTIONS.length - 1) {
        setCurrentQuestion(prev => prev + 1);
      } else {
        setStep('analyzing');
      }
    }, 400);
  };

  useEffect(() => {
    if (step === 'analyzing') {
      const timer = setTimeout(() => {
        saveData(); 
        setStep('result');
      }, 2500);
      return () => clearTimeout(timer);
    }
  }, [step]);

  const saveData = () => {
    const newEntry = {
      id: Date.now(),
      timestamp: new Date().toLocaleString(),
      ...formData,
      score: score,
      resultType: score >= 4 ? 'INGENIERO (Arduino/VEX)' : 'CREATIVO (Lego/Kids)',
    };
    
    const updatedDb = [...database, newEntry];
    setDatabase(updatedDb);
    localStorage.setItem('roboticMindsDB_v3', JSON.stringify(updatedDb));
  };

  // --- LÓGICA DE DESCARGA EXCEL ---
  const downloadXLS = () => {
    if (database.length === 0) {
      alert("No hay datos para exportar aún.");
      return;
    }
    let tableHTML = `
      <html xmlns:o="urn:schemas-microsoft-com:office:office" xmlns:x="urn:schemas-microsoft-com:office:excel" xmlns="http://www.w3.org/TR/REC-html40">
      <head><meta charset="UTF-8"></head>
      <body>
        <table border="1">
          <thead>
            <tr style="background-color: #4F46E5; color: white;">
              <th>Fecha y Hora</th><th>Padre</th><th>Teléfono</th><th>Alumno</th><th>Edad</th><th>Colegio</th><th>Puntaje</th><th>Perfil</th>
            </tr>
          </thead>
          <tbody>
            ${database.map(row => `
              <tr>
                <td>${row.timestamp}</td><td>${row.parentName}</td><td style="mso-number-format:'@'">${row.phone}</td>
                <td>${row.studentName}</td><td>${row.age}</td><td>${row.school}</td><td style="text-align: center;">${row.score}/5</td><td>${row.resultType}</td>
              </tr>
            `).join('')}
          </tbody>
        </table>
      </body></html>`;
    const blob = new Blob([tableHTML], { type: 'application/vnd.ms-excel' });
    const url = URL.createObjectURL(blob);
    const link = document.createElement("a");
    link.href = url;
    link.download = `Base_Datos_Torneo_${new Date().toLocaleDateString().replace(/\//g, '-')}.xls`;
    document.body.appendChild(link);
    link.click();
    document.body.removeChild(link);
  };

  const copyToClipboard = () => {
    if (database.length === 0) return;
    const headers = "Fecha\tPadre\tTeléfono\tAlumno\tEdad\tColegio\tPuntaje\tPerfil";
    const rows = database.map(r => `${r.timestamp}\t${r.parentName}\t${r.phone}\t${r.studentName}\t${r.age}\t${r.school}\t${r.score}\t${r.resultType}`).join('\n');
    navigator.clipboard.writeText(`${headers}\n${rows}`).then(() => {
      setCopied(true);
      setTimeout(() => setCopied(false), 2000);
      alert("¡Datos copiados!");
    });
  };

  const deleteEntry = (id) => {
    if (confirm("¿Seguro que deseas borrar este registro?")) {
      const updatedDb = database.filter(item => item.id !== id);
      setDatabase(updatedDb);
      localStorage.setItem('roboticMindsDB_v3', JSON.stringify(updatedDb));
    }
  };

  const resetApp = () => {
    setFormData({ parentName: '', phone: '', studentName: '', age: '', school: '' });
    setCurrentQuestion(0);
    setAnswers({});
    setScore(0);
    setStep('landing');
  };

  // --- VISTAS ---

  if (step === 'landing') {
    return (
      <div className="min-h-screen bg-slate-900 flex flex-col items-center justify-center p-4 text-center text-white font-sans relative overflow-hidden">
        <div className="absolute inset-0 opacity-10 bg-[url('https://www.transparenttextures.com/patterns/carbon-fibre.png')]"></div>
        
        <div className="z-10 max-w-2xl w-full bg-slate-800/90 p-8 rounded-3xl border border-blue-500/50 shadow-[0_0_50px_rgba(59,130,246,0.3)] backdrop-blur-sm">
          
          <div className="mb-6 flex justify-center animate-fade-in relative w-full">
            {/* SIN LOGO - SOLO ICONO */}
            <Cpu className="w-24 h-24 text-blue-400 animate-pulse drop-shadow-[0_0_10px_rgba(59,130,246,0.5)]" />
          </div>

          <h1 className="text-4xl md:text-6xl font-extrabold mb-2 tracking-tighter bg-gradient-to-r from-blue-400 to-purple-500 bg-clip-text text-transparent">
            EL GRAN RETO
          </h1>
          <h2 className="text-2xl md:text-3xl font-bold mb-8 text-white tracking-widest border-t border-b border-blue-500/30 py-2 inline-block">
            ROBOTIC MINDS
          </h2>
          
          <button 
            onClick={handleStart}
            className="w-full py-5 text-2xl font-bold bg-blue-600 hover:bg-blue-500 text-white rounded-xl transition-all transform hover:scale-105 shadow-lg flex items-center justify-center gap-3"
          >
            <Play fill="currentColor" className="w-8 h-8"/> INICIAR DIAGNÓSTICO
          </button>
        </div>
        
        <button onClick={() => setStep('admin')} className="absolute bottom-6 right-6 text-slate-600 hover:text-slate-400 flex items-center gap-1 text-sm bg-slate-800 p-2 rounded-lg opacity-50 hover:opacity-100">
          <Lock className="w-4 h-4" /> Admin
        </button>
      </div>
    );
  }

  if (step === 'admin') {
    return (
      <div className="min-h-screen bg-slate-100 p-4 font-sans text-slate-800 overflow-auto">
        <div className="max-w-7xl mx-auto">
          <div className="flex flex-col md:flex-row justify-between items-center mb-6 bg-white p-4 rounded-xl shadow-sm gap-4">
            <div className="flex items-center gap-4">
               {/* Icono Admin */}
               <Cpu className="w-10 h-10 text-slate-700" />
               <h2 className="text-2xl font-bold flex items-center gap-2 border-l-2 border-slate-200 pl-4">
                 <Table className="text-blue-600" /> Base de Datos ({database.length})
               </h2>
            </div>
            <div className="flex flex-wrap gap-2 justify-center">
              <button onClick={() => setStep('landing')} className="px-4 py-2 text-slate-600 hover:bg-slate-100 rounded-lg font-medium border border-slate-300">Volver</button>
              <button onClick={copyToClipboard} className={`px-4 py-2 text-white rounded-lg flex items-center gap-2 font-bold shadow-sm transition-colors ${copied ? 'bg-blue-800' : 'bg-blue-600 hover:bg-blue-700'}`}>
                {copied ? <Check className="w-5 h-5"/> : <Copy className="w-5 h-5" />} {copied ? '¡Copiado!' : 'Copiar Tabla'}
              </button>
              <button onClick={downloadXLS} className="px-4 py-2 bg-green-600 text-white rounded-lg hover:bg-green-700 flex items-center gap-2 font-bold shadow-sm">
                <Download className="w-5 h-5" /> Descargar Excel
              </button>
            </div>
          </div>
          <div className="bg-white rounded-xl shadow-sm overflow-hidden border border-slate-200">
            {/* Tabla... */}
            {database.length === 0 ? <div className="p-10 text-center text-gray-400"><p>No hay registros todavía.</p></div> : (
              <div className="overflow-x-auto">
                <table className="w-full text-sm text-left border-collapse">
                  <thead className="text-xs text-slate-500 uppercase bg-slate-100 border-b">
                    <tr>
                      <th className="px-4 py-3 border-r">Fecha</th><th className="px-4 py-3 border-r">Padre</th><th className="px-4 py-3 border-r">Teléfono</th>
                      <th className="px-4 py-3 border-r">Alumno</th><th className="px-4 py-3 border-r">Edad</th><th className="px-4 py-3 border-r bg-yellow-50">Colegio</th>
                      <th className="px-4 py-3 border-r">Puntaje</th><th className="px-4 py-3 border-r">Perfil</th><th className="px-4 py-3 text-center">Acción</th>
                    </tr>
                  </thead>
                  <tbody>
                    {database.map((row) => (
                      <tr key={row.id} className="bg-white border-b hover:bg-slate-50">
                        <td className="px-4 py-3 text-gray-500 border-r">{row.timestamp.split(',')[1]}</td>
                        <td className="px-4 py-3 font-medium text-slate-900 border-r">{row.parentName}</td>
                        <td className="px-4 py-3 font-mono text-blue-600 border-r">{row.phone}</td>
                        <td className="px-4 py-3 border-r">{row.studentName}</td>
                        <td className="px-4 py-3 border-r">{row.age}</td>
                        <td className="px-4 py-3 border-r bg-yellow-50 font-medium text-slate-700">{row.school}</td>
                        <td className="px-4 py-3 border-r text-center"><span className={`px-2 py-1 rounded-full text-xs font-bold ${row.score >= 4 ? 'bg-green-100 text-green-700' : 'bg-orange-100 text-orange-700'}`}>{row.score}/5</span></td>
                        <td className="px-4 py-3 text-xs font-bold text-slate-600 border-r">{row.resultType.split(' ')[0]}</td>
                        <td className="px-4 py-3 text-center"><button onClick={() => deleteEntry(row.id)} className="text-red-400 hover:text-red-600"><Trash2 className="w-4 h-4" /></button></td>
                      </tr>
                    ))}
                  </tbody>
                </table>
              </div>
            )}
          </div>
        </div>
      </div>
    );
  }

  if (step === 'register') {
    return (
      <div className="min-h-screen bg-slate-900 flex items-center justify-center p-4">
        <div className="w-full max-w-lg bg-slate-800 p-8 rounded-2xl shadow-2xl border-t-4 border-blue-500 relative">
          <button onClick={() => setStep('landing')} className="absolute top-4 right-4 text-gray-500 hover:text-white"><X className="w-6 h-6" /></button>
          
          <div className="flex justify-center mb-6">
             {/* SIN LOGO - SOLO TEXTO */}
             <h2 className="text-2xl font-bold text-blue-400 tracking-wider">ROBOTIC MINDS</h2>
          </div>

          <h3 className="text-2xl font-bold text-white mb-6 flex items-center justify-center gap-2 border-b border-slate-700 pb-4">
            <User className="text-blue-400" /> Registro de Aspirante
          </h3>
          <form onSubmit={handleRegisterSubmit} className="space-y-4">
            <div><label className="block text-sm font-medium text-gray-400 mb-1">Nombre del Representante</label><input type="text" name="parentName" required value={formData.parentName} onChange={handleInputChange} className="w-full p-3 bg-slate-700 text-white rounded-lg border border-slate-600 focus:border-blue-500 outline-none" placeholder="Nombre y Apellido"/></div>
            <div><label className="block text-sm font-medium text-gray-400 mb-1">Celular (WhatsApp)</label><input type="tel" name="phone" required value={formData.phone} onChange={handleInputChange} className="w-full p-3 bg-slate-700 text-white rounded-lg border border-slate-600 focus:border-blue-500 outline-none" placeholder="Ej: 0991234567"/></div>
            <div className="grid grid-cols-2 gap-4">
              <div><label className="block text-sm font-medium text-gray-400 mb-1">Nombre Estudiante</label><input type="text" name="studentName" required value={formData.studentName} onChange={handleInputChange} className="w-full p-3 bg-slate-700 text-white rounded-lg border border-slate-600 focus:border-blue-500 outline-none"/></div>
              <div><label className="block text-sm font-medium text-gray-400 mb-1">Edad</label><select name="age" required value={formData.age} onChange={handleInputChange} className="w-full p-3 bg-slate-700 text-white rounded-lg border border-slate-600 focus:border-blue-500 outline-none"><option value="">Selecciona</option><option value="5-7">5 - 7 años</option><option value="8-10">8 - 10 años</option><option value="11-13">11 - 13 años</option><option value="14+">14+ años</option></select></div>
            </div>
            <div><label className="block text-sm font-medium text-blue-400 mb-1 flex items-center gap-2"><Building className="w-4 h-4" /> Colegio / Institución</label><input type="text" name="school" required value={formData.school} onChange={handleInputChange} className="w-full p-3 bg-slate-700 text-white rounded-lg border border-blue-500/50 focus:border-blue-500 outline-none" placeholder="Ej: Unidad Educativa..."/></div>
            <button type="submit" className="w-full mt-6 py-4 font-bold bg-green-600 hover:bg-green-500 text-white rounded-xl transition-all shadow-lg text-lg">COMENZAR PRUEBA</button>
          </form>
        </div>
      </div>
    );
  }

  if (step === 'quiz') {
    const question = QUESTIONS[currentQuestion];
    const progress = ((currentQuestion + 1) / QUESTIONS.length) * 100;
    return (
      <div className="min-h-screen bg-slate-900 flex flex-col items-center p-4">
        
        <div className="w-full max-w-2xl flex justify-between items-center mt-2 mb-4">
           {/* SIN LOGO - SOLO TEXTO PEQUEÑO */}
           <span className="text-blue-400 font-bold tracking-wider">ROBOTIC MINDS</span>
           <span className="text-slate-500 text-xs font-bold uppercase tracking-widest">Diagnóstico de Talento</span>
        </div>

        <div className="w-full max-w-2xl h-3 bg-slate-700 rounded-full mb-8 overflow-hidden">
          <div className="h-full bg-gradient-to-r from-blue-500 to-purple-500 transition-all duration-500 ease-out" style={{ width: `${progress}%` }}></div>
        </div>
        <div className="w-full max-w-2xl bg-white rounded-2xl shadow-2xl overflow-hidden animate-fade-in-up">
          <div className="bg-slate-50 p-6 flex items-center justify-between border-b border-gray-200">
            <span className="text-gray-500 font-bold tracking-wider text-sm">PREGUNTA {currentQuestion + 1} / {QUESTIONS.length}</span>
            <div className="bg-blue-50 p-2 rounded-full border border-blue-100 shadow-inner">
              {question.animation}
            </div>
          </div>
          <div className="p-8">
            <h2 className="text-2xl font-bold text-slate-800 mb-8 leading-snug">{question.question}</h2>
            <div className="space-y-4">
              {question.options.map((option) => (
                <button key={option.id} onClick={() => handleAnswerOption(option.correct, option.id)} className="w-full text-left p-5 rounded-xl border-2 border-gray-100 hover:border-blue-500 hover:bg-blue-50 transition-all group flex items-center shadow-sm hover:shadow-md">
                  <span className="w-10 h-10 rounded-full bg-gray-200 group-hover:bg-blue-600 group-hover:text-white flex items-center justify-center font-bold mr-4 transition-colors shrink-0">{option.id}</span>
                  <span className="text-lg text-gray-700 font-medium group-hover:text-blue-900">{option.text}</span>
                </button>
              ))}
            </div>
          </div>
        </div>
      </div>
    );
  }

  if (step === 'analyzing') {
    return (
      <div className="min-h-screen bg-black flex flex-col items-center justify-center text-center p-4">
        {/* SIN LOGO - SOLO TEXTO */}
        <h2 className="text-3xl font-bold text-blue-500 mb-10 tracking-widest animate-pulse">ROBOTIC MINDS</h2>
        <div className="relative w-40 h-40 mb-8">
          <div className="absolute inset-0 border-4 border-blue-500/30 rounded-full animate-ping"></div>
          <div className="absolute inset-4 border-4 border-t-blue-500 border-r-transparent border-b-blue-500 border-l-transparent rounded-full animate-spin"></div>
          <div className="absolute inset-0 flex items-center justify-center flex-col"><Cpu className="text-white w-10 h-10 mb-2" /><span className="text-xs text-blue-400 font-mono">AI PROCESSING</span></div>
        </div>
        <h2 className="text-2xl font-mono text-white animate-pulse">ANALIZANDO...</h2>
      </div>
    );
  }

  if (step === 'result') {
    const isHighLevel = score >= 4;
    return (
      <div className="min-h-screen bg-slate-900 flex items-center justify-center p-4">
        <div className="w-full max-w-lg bg-white rounded-3xl shadow-[0_0_60px_rgba(255,255,255,0.1)] overflow-hidden text-center relative animate-fade-in">
          <div className={`p-10 ${isHighLevel ? 'bg-gradient-to-br from-indigo-600 to-purple-700' : 'bg-gradient-to-br from-orange-500 to-red-500'} text-white relative`}>
             <div className="absolute top-4 left-0 right-0 flex justify-center opacity-80">
               {/* SIN LOGO - SOLO TEXTO */}
               <span className="font-bold tracking-widest text-sm">ROBOTIC MINDS</span>
            </div>
            
            <div className="flex justify-center mb-4 mt-8">
               {isHighLevel ? <ShieldCheck className="w-24 h-24 drop-shadow-lg" /> : <Zap className="w-24 h-24 drop-shadow-lg" />}
            </div>
            <h1 className="text-4xl font-extrabold mb-2 tracking-tight">¡DIAGNÓSTICO LISTO!</h1>
          </div>
          <div className="p-8 bg-slate-50">
            <div className="bg-white p-6 rounded-2xl shadow-sm border border-gray-200 mb-6 relative overflow-hidden">
               <div className="absolute top-0 left-0 w-2 h-full bg-slate-300"></div>
              <h3 className="text-gray-400 text-xs font-bold uppercase tracking-widest mb-2">Puntaje Final</h3>
              <div className="flex items-center justify-center gap-2 mb-2">
                <span className="text-6xl font-black text-slate-800">{score}</span>
                <span className="text-xl text-gray-400 font-medium self-end mb-3">/ 5</span>
              </div>
              <div className="bg-yellow-50 border border-yellow-200 p-4 rounded-xl text-left mt-4 shadow-sm">
                <p className="text-xs text-yellow-700 font-bold mb-1 uppercase flex items-center gap-1"><AlertTriangle className="w-3 h-3" /> Script para Instructor:</p>
                <p className="text-sm text-slate-800 font-medium leading-relaxed">
                  {isHighLevel ? "🎯 PERFIL: ARDUINO/COMPETENCIA. El estudiante tiene lógica avanzada. Recomendar: Curso de Programación C++ o Club VEX." : "🎨 PERFIL: CREATIVO/KIDS. Gran potencial creativo y visual. Recomendar: Lego EV3 o VEX GO para iniciar."}
                </p>
              </div>
            </div>
            <div className="bg-red-50 p-4 rounded-xl border border-red-100 mb-6">
              <p className="text-red-600 font-bold text-sm flex items-center justify-center gap-2"><AlertTriangle className="w-4 h-4" /> ATENCIÓN</p>
              <p className="text-sm text-red-500 mt-1">No cierres esta pantalla. Entrega el dispositivo para validar tu Beca.</p>
            </div>
            <button onClick={resetApp} className="w-full py-4 bg-slate-800 hover:bg-slate-700 text-white rounded-xl font-bold text-lg shadow-lg transition-all">SIGUIENTE ALUMNO</button>
          </div>
        </div>
      </div>
    );
  }
}
