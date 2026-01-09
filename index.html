import React, { useState } from 'react';
import { motion, AnimatePresence } from 'framer-motion';
import { Button } from "@/components/ui/button";
import { Progress } from "@/components/ui/progress";
import { Brain, ChevronRight, ChevronLeft, Sparkles, Shield, Clock, CheckCircle2 } from 'lucide-react';

const perguntas = [
  {
    id: 1,
    texto: "Com que frequência você tem dificuldade em manter a atenção quando está fazendo trabalhos monótonos ou repetitivos?",
  },
  {
    id: 2,
    texto: "Com que frequência você se distrai facilmente com estímulos externos ou pensamentos não relacionados?",
  },
  {
    id: 3,
    texto: "Com que frequência você tem dificuldade em organizar tarefas e atividades?",
  },
  {
    id: 4,
    texto: "Com que frequência você evita ou reluta em iniciar tarefas que exigem esforço mental prolongado?",
  },
  {
    id: 5,
    texto: "Com que frequência você perde objetos necessários para tarefas ou atividades do dia a dia?",
  },
  {
    id: 6,
    texto: "Com que frequência você se sente inquieto(a) ou tem dificuldade em ficar parado(a)?",
  },
  {
    id: 7,
    texto: "Com que frequência você interrompe os outros ou tem dificuldade em esperar sua vez?",
  },
  {
    id: 8,
    texto: "Com que frequência você tem dificuldade em seguir instruções e terminar tarefas?",
  },
  {
    id: 9,
    texto: "Com que frequência você se sente mentalmente esgotado(a) após tarefas que exigem concentração?",
  },
  {
    id: 10,
    texto: "Com que frequência você esquece compromissos, prazos ou tarefas importantes?",
  },
  {
    id: 11,
    texto: "Com que frequência você tem dificuldade em relaxar durante momentos de lazer?",
  },
  {
    id: 12,
    texto: "Com que frequência você fala excessivamente em situações sociais?",
  },
  {
    id: 13,
    texto: "Com que frequência você age impulsivamente sem pensar nas consequências?",
  },
  {
    id: 14,
    texto: "Com que frequência você tem dificuldade em priorizar tarefas por ordem de importância?",
  },
  {
    id: 15,
    texto: "Com que frequência você se sente sobrecarregado(a) com as responsabilidades do dia a dia?",
  },
];

const opcoes = [
  { valor: 0, label: "Nunca" },
  { valor: 1, label: "Raramente" },
  { valor: 2, label: "Às vezes" },
  { valor: 3, label: "Frequentemente" },
  { valor: 4, label: "Muito frequentemente" },
];

export default function TesteADHD() {
  const [etapa, setEtapa] = useState('inicio'); // inicio, teste, resultado
  const [perguntaAtual, setPerguntaAtual] = useState(0);
  const [respostas, setRespostas] = useState({});

  const progresso = ((perguntaAtual + 1) / perguntas.length) * 100;

  const handleResposta = (valor) => {
    setRespostas({ ...respostas, [perguntaAtual]: valor });
  };

  const proximaPergunta = () => {
    if (perguntaAtual < perguntas.length - 1) {
      setPerguntaAtual(perguntaAtual + 1);
    } else {
      setEtapa('resultado');
    }
  };

  const perguntaAnterior = () => {
    if (perguntaAtual > 0) {
      setPerguntaAtual(perguntaAtual - 1);
    }
  };

  const iniciarTeste = () => {
    setEtapa('teste');
    setPerguntaAtual(0);
    setRespostas({});
  };

  // Tela Inicial
  if (etapa === 'inicio') {
    return (
      <div className="min-h-screen bg-gradient-to-br from-slate-50 via-blue-50 to-indigo-50">
        <div className="max-w-4xl mx-auto px-4 py-12 md:py-20">
          <motion.div
            initial={{ opacity: 0, y: 20 }}
            animate={{ opacity: 1, y: 0 }}
            transition={{ duration: 0.6 }}
            className="text-center"
          >
            <div className="inline-flex items-center justify-center w-20 h-20 rounded-2xl bg-gradient-to-br from-indigo-500 to-blue-600 shadow-xl shadow-indigo-200 mb-8">
              <Brain className="w-10 h-10 text-white" />
            </div>
            
            <h1 className="text-4xl md:text-5xl font-bold text-slate-800 mb-4 tracking-tight">
              Teste de Avaliação
              <span className="block text-transparent bg-clip-text bg-gradient-to-r from-indigo-600 to-blue-500">
                TDAH
              </span>
            </h1>
            
            <p className="text-lg text-slate-600 max-w-2xl mx-auto mb-12 leading-relaxed">
              Descubra se você apresenta sinais de Transtorno de Déficit de Atenção e Hiperatividade através de nossa avaliação científica com 15 perguntas cuidadosamente elaboradas.
            </p>

            <div className="grid md:grid-cols-3 gap-6 mb-12">
              <motion.div
                initial={{ opacity: 0, y: 20 }}
                animate={{ opacity: 1, y: 0 }}
                transition={{ delay: 0.2 }}
                className="bg-white/70 backdrop-blur-sm rounded-2xl p-6 border border-slate-100 shadow-sm"
              >
                <div className="w-12 h-12 rounded-xl bg-indigo-100 flex items-center justify-center mb-4 mx-auto">
                  <Clock className="w-6 h-6 text-indigo-600" />
                </div>
                <h3 className="font-semibold text-slate-800 mb-2">5-7 minutos</h3>
                <p className="text-sm text-slate-500">Tempo médio para completar o teste</p>
              </motion.div>

              <motion.div
                initial={{ opacity: 0, y: 20 }}
                animate={{ opacity: 1, y: 0 }}
                transition={{ delay: 0.3 }}
                className="bg-white/70 backdrop-blur-sm rounded-2xl p-6 border border-slate-100 shadow-sm"
              >
                <div className="w-12 h-12 rounded-xl bg-blue-100 flex items-center justify-center mb-4 mx-auto">
                  <CheckCircle2 className="w-6 h-6 text-blue-600" />
                </div>
                <h3 className="font-semibold text-slate-800 mb-2">15 Perguntas</h3>
                <p className="text-sm text-slate-500">Baseadas em critérios diagnósticos</p>
              </motion.div>

              <motion.div
                initial={{ opacity: 0, y: 20 }}
                animate={{ opacity: 1, y: 0 }}
                transition={{ delay: 0.4 }}
                className="bg-white/70 backdrop-blur-sm rounded-2xl p-6 border border-slate-100 shadow-sm"
              >
                <div className="w-12 h-12 rounded-xl bg-emerald-100 flex items-center justify-center mb-4 mx-auto">
                  <Shield className="w-6 h-6 text-emerald-600" />
                </div>
                <h3 className="font-semibold text-slate-800 mb-2">100% Confidencial</h3>
                <p className="text-sm text-slate-500">Suas respostas são privadas</p>
              </motion.div>
            </div>

            <motion.div
              initial={{ opacity: 0, scale: 0.95 }}
              animate={{ opacity: 1, scale: 1 }}
              transition={{ delay: 0.5 }}
            >
              <Button
                onClick={iniciarTeste}
                className="bg-gradient-to-r from-indigo-600 to-blue-500 hover:from-indigo-700 hover:to-blue-600 text-white px-10 py-6 rounded-xl text-lg font-semibold shadow-xl shadow-indigo-200 transition-all hover:scale-105"
              >
                Iniciar Teste Gratuito
                <ChevronRight className="w-5 h-5 ml-2" />
              </Button>
            </motion.div>

            <p className="text-xs text-slate-400 mt-8 max-w-md mx-auto">
              Este teste não substitui uma avaliação profissional. Consulte um especialista para um diagnóstico adequado.
            </p>
          </motion.div>
        </div>
      </div>
    );
  }

  // Tela do Teste
  if (etapa === 'teste') {
    return (
      <div className="min-h-screen bg-gradient-to-br from-slate-50 via-blue-50 to-indigo-50">
        <div className="max-w-2xl mx-auto px-4 py-8 md:py-12">
          {/* Header */}
          <div className="mb-8">
            <div className="flex items-center justify-between mb-4">
              <div className="flex items-center gap-3">
                <div className="w-10 h-10 rounded-xl bg-gradient-to-br from-indigo-500 to-blue-600 flex items-center justify-center">
                  <Brain className="w-5 h-5 text-white" />
                </div>
                <span className="font-semibold text-slate-700">Teste TDAH</span>
              </div>
              <span className="text-sm font-medium text-slate-500">
                {perguntaAtual + 1} de {perguntas.length}
              </span>
            </div>
            <Progress value={progresso} className="h-2 bg-slate-200" />
          </div>

          {/* Pergunta */}
          <AnimatePresence mode="wait">
            <motion.div
              key={perguntaAtual}
              initial={{ opacity: 0, x: 20 }}
              animate={{ opacity: 1, x: 0 }}
              exit={{ opacity: 0, x: -20 }}
              transition={{ duration: 0.3 }}
              className="bg-white rounded-3xl shadow-xl shadow-slate-200/50 border border-slate-100 p-8 md:p-10"
            >
              <div className="mb-2">
                <span className="inline-flex items-center px-3 py-1 rounded-full bg-indigo-50 text-indigo-600 text-sm font-medium">
                  Pergunta {perguntaAtual + 1}
                </span>
              </div>
              
              <h2 className="text-xl md:text-2xl font-semibold text-slate-800 mb-8 leading-relaxed">
                {perguntas[perguntaAtual].texto}
              </h2>

              <div className="space-y-3">
                {opcoes.map((opcao) => (
                  <motion.button
                    key={opcao.valor}
                    whileHover={{ scale: 1.01 }}
                    whileTap={{ scale: 0.99 }}
                    onClick={() => handleResposta(opcao.valor)}
                    className={`w-full text-left p-4 rounded-xl border-2 transition-all ${
                      respostas[perguntaAtual] === opcao.valor
                        ? 'border-indigo-500 bg-indigo-50 text-indigo-700'
                        : 'border-slate-200 hover:border-slate-300 hover:bg-slate-50 text-slate-700'
                    }`}
                  >
                    <div className="flex items-center gap-4">
                      <div className={`w-5 h-5 rounded-full border-2 flex items-center justify-center transition-all ${
                        respostas[perguntaAtual] === opcao.valor
                          ? 'border-indigo-500 bg-indigo-500'
                          : 'border-slate-300'
                      }`}>
                        {respostas[perguntaAtual] === opcao.valor && (
                          <div className="w-2 h-2 rounded-full bg-white" />
                        )}
                      </div>
                      <span className="font-medium">{opcao.label}</span>
                    </div>
                  </motion.button>
                ))}
              </div>
            </motion.div>
          </AnimatePresence>

          {/* Navegação */}
          <div className="flex justify-between mt-8">
            <Button
              variant="ghost"
              onClick={perguntaAnterior}
              disabled={perguntaAtual === 0}
              className="text-slate-600 hover:text-slate-800"
            >
              <ChevronLeft className="w-5 h-5 mr-1" />
              Anterior
            </Button>

            <Button
              onClick={proximaPergunta}
              disabled={respostas[perguntaAtual] === undefined}
              className="bg-gradient-to-r from-indigo-600 to-blue-500 hover:from-indigo-700 hover:to-blue-600 text-white px-8"
            >
              {perguntaAtual === perguntas.length - 1 ? 'Finalizar' : 'Próxima'}
              <ChevronRight className="w-5 h-5 ml-1" />
            </Button>
          </div>
        </div>
      </div>
    );
  }

  // Tela de Resultado
  if (etapa === 'resultado') {
    return (
      <div className="min-h-screen bg-gradient-to-br from-slate-50 via-blue-50 to-indigo-50">
        <div className="max-w-2xl mx-auto px-4 py-12 md:py-20">
          <motion.div
            initial={{ opacity: 0, y: 20 }}
            animate={{ opacity: 1, y: 0 }}
            transition={{ duration: 0.6 }}
            className="text-center"
          >
            <div className="inline-flex items-center justify-center w-24 h-24 rounded-full bg-gradient-to-br from-emerald-400 to-teal-500 shadow-xl shadow-emerald-200 mb-8">
              <CheckCircle2 className="w-12 h-12 text-white" />
            </div>

            <h1 className="text-3xl md:text-4xl font-bold text-slate-800 mb-4">
              Teste Concluído!
            </h1>

            <p className="text-lg text-slate-600 mb-8 max-w-md mx-auto">
              Você respondeu todas as 15 perguntas. Seu resultado personalizado está pronto para ser revelado.
            </p>

            <motion.div
              initial={{ opacity: 0, scale: 0.95 }}
              animate={{ opacity: 1, scale: 1 }}
              transition={{ delay: 0.3 }}
              className="bg-white rounded-3xl shadow-xl shadow-slate-200/50 border border-slate-100 p-8 md:p-10 mb-8"
            >
              <div className="flex items-center justify-center gap-2 mb-6">
                <Sparkles className="w-5 h-5 text-amber-500" />
                <span className="text-sm font-semibold text-amber-600 uppercase tracking-wide">
                  Oferta Especial
                </span>
              </div>

              <h2 className="text-2xl font-bold text-slate-800 mb-3">
                Obtenha seu Resultado Completo
              </h2>

              <p className="text-slate-600 mb-6">
                Receba uma análise detalhada com sua pontuação, interpretação dos resultados e recomendações personalizadas.
              </p>

              <ul className="text-left space-y-3 mb-8 max-w-sm mx-auto">
                <li className="flex items-center gap-3 text-slate-700">
                  <div className="w-5 h-5 rounded-full bg-emerald-100 flex items-center justify-center flex-shrink-0">
                    <CheckCircle2 className="w-3 h-3 text-emerald-600" />
                  </div>
                  Pontuação detalhada por categoria
                </li>
                <li className="flex items-center gap-3 text-slate-700">
                  <div className="w-5 h-5 rounded-full bg-emerald-100 flex items-center justify-center flex-shrink-0">
                    <CheckCircle2 className="w-3 h-3 text-emerald-600" />
                  </div>
                  Interpretação científica dos resultados
                </li>
                <li className="flex items-center gap-3 text-slate-700">
                  <div className="w-5 h-5 rounded-full bg-emerald-100 flex items-center justify-center flex-shrink-0">
                    <CheckCircle2 className="w-3 h-3 text-emerald-600" />
                  </div>
                  Recomendações personalizadas
                </li>
                <li className="flex items-center gap-3 text-slate-700">
                  <div className="w-5 h-5 rounded-full bg-emerald-100 flex items-center justify-center flex-shrink-0">
                    <CheckCircle2 className="w-3 h-3 text-emerald-600" />
                  </div>
                  PDF para download
                </li>
              </ul>

              <div className="mb-6">
                <div className="flex items-baseline justify-center gap-1">
                  <span className="text-sm text-slate-500 line-through">R$ 29,90</span>
                </div>
                <div className="flex items-baseline justify-center gap-1">
                  <span className="text-4xl font-bold text-slate-800">R$ 9,49</span>
                </div>
                <p className="text-sm text-emerald-600 font-medium mt-1">
                  Economize 68% - Apenas hoje!
                </p>
              </div>

              <Button
                className="w-full bg-gradient-to-r from-amber-500 to-orange-500 hover:from-amber-600 hover:to-orange-600 text-white py-6 rounded-xl text-lg font-semibold shadow-lg shadow-amber-200 transition-all hover:scale-[1.02]"
              >
                <Sparkles className="w-5 h-5 mr-2" />
                Obter Meu Resultado - R$ 9,49
              </Button>

              <div className="flex items-center justify-center gap-2 mt-4 text-sm text-slate-500">
                <Shield className="w-4 h-4" />
                Pagamento 100% seguro
              </div>
            </motion.div>

            <p className="text-xs text-slate-400 max-w-md mx-auto">
              Este teste é apenas para fins informativos e não constitui diagnóstico médico. Consulte um profissional de saúde para avaliação completa.
            </p>
          </motion.div>
        </div>
      </div>
    );
  }

  return null;
}
