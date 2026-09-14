import { useState } from "react";

const BRAND = {
  red: "#D42027",
  redDark: "#A01A1F",
  redLight: "#FDF0F0",
  charcoal: "#1A1A1A",
  gray: "#6B7280",
  grayLight: "#F3F4F6",
  grayMid: "#E5E7EB",
  white: "#FFFFFF",
};

const meals = [
  {
    id: "cafe",
    label: "Café da Manhã",
    icon: "☀️",
    suggestion: "Pão com ovo gourmet",
    items: [
      {
        main: "Pão de Forma Integral, 2 Fatias (50g)",
        subs: ["Cuscuz de Milho Cozido (110g)", "Macaxeira Cozida (100g)", "Batata Doce Cozida (160g)", "Goma de Tapioca (40g)", "Batata Inglesa Cozida (240g)", "Inhame Cozido (125g)"],
      },
      {
        main: "Ovo de Galinha Inteiro, 2 Unidades (90g)",
        subs: ["Sardinha em Lata Drenada (45g)", "Peito de Frango Sem Pele Grelhado (85g)", "Carne Bovina Cozida/Grelhada Magra (60g)", "Carne Bovina Moída Patinho (85g)", "Lombo de Porco Assado (65g)", "Atum Sólido ao Natural (100g)"],
      },
      {
        main: "Queijo Muçarela, 1 Fatia (20g)",
        subs: ["Requeijão Cremoso Light (30g)", "Queijo Cottage (70g)", "Creme de Ricota Light (40g)", "Leite de Vaca Desnatado (185g)", "Iogurte Natural Desnatado (175g)", "Leite em Pó Desnatado (15g)"],
      },
      { main: "Fruta (Anexo 1), 1 Porção", subs: [] },
      {
        main: "Farelo de Aveia (Oat Bran Quaker), 2 Col. sopa (20g)",
        subs: ["Granola Comum (9g)", "Semente de Chia (8g)", "Semente de Abóbora (6g)", "Semente de Girassol (5g)"],
      },
    ],
  },
  {
    id: "almoco",
    label: "Almoço",
    icon: "🍽️",
    suggestion: "Prato completo com legumes coloridos",
    items: [
      {
        main: "Arroz Branco Cozido, 2 Col. servir (110g)",
        subs: ["Batata Inglesa Cozida (270g)", "Abóbora Cozida (290g)", "Arroz Integral Cozido (110g)", "Macarrão Cozido (85g)"],
      },
      {
        main: "Peito de Frango Sem Pele Cozido, 1.5 Filé (150g)",
        subs: ["Peito de Frango Cru (205g)", "Carne Bovina Magra (110g)", "Carne Bovina Crua (180g)", "Peixe Assado/Grelhado (205g)", "Lombo de Porco Assado (115g)", "Bife de Fígado Grelhado (105g)"],
      },
      {
        main: "Feijão Cozido, 6 Col. sopa (102g)",
        subs: ["Grão de Bico Cozido (65g)", "Ervilha em Vagem Cozida (115g)"],
      },
      { main: "Legumes e Verduras (Anexo 2), 1 Porção (150g)", subs: [] },
      { main: "Fruta rica em Vitamina C (Anexo 1), 1 Porção", subs: [] },
      {
        main: "Doce de Leite Industrializado, 1 Col. sopa (20g)",
        subs: ["Leite Condensado Semidesnatado (20g)"],
      },
    ],
  },
  {
    id: "lanche1",
    label: "Lanche da Tarde",
    icon: "🥤",
    suggestion: "Opção 1 — Iogurte com frutas e castanhas",
    items: [
      { main: "Fruta (Anexo 1), 2 Porções", subs: [] },
      {
        main: "Iogurte Natural, 1 Pote 170ml (170g)",
        subs: ["Leite em Pó Integral (20g)", "Leite de Vaca Integral (170g)", "Iogurte Orgânico Qualquer Sabor (105g)"],
      },
      {
        main: "Castanha de Caju, 15 Unidades (37,5g)",
        subs: ["Pasta de Amendoim POWER1ONE (35g)", "Nozes (30g)", "Amêndoa Crua (35g)", "Castanha-do-Pará, 8 Un. (32g)"],
      },
      { main: "Whey Protein Concentrado (30g)", subs: [] },
    ],
  },
  {
    id: "lanche2",
    label: "Lanche da Tarde (Op. 2)",
    icon: "🥪",
    suggestion: "Sanduíche de Atum",
    items: [
      {
        main: "Pão de Forma Integral, 2 Fatias (50g)",
        subs: ["Rap10 Fit (50g)", "Goma de Tapioca (40g)", "Pão Francês (40g)", "Batata Inglesa Cozida (240g)", "Batata Doce Cozida (160g)", "Arroz Branco Cozido (95g)"],
      },
      {
        main: "Filé de Atum em Azeite de Oliva (80g)",
        subs: ["Frango Desfiado Peito (100g)", "Carne Bovina Moída Patinho (100g)", "Salmão Sem Pele Grelhado (65g)", "Lombo de Porco Assado (75g)", "Proteína de Soja Texturizada (85g)", "Carne Bovina Magra (75g)"],
      },
      {
        main: "Requeijão Cremoso (30g)",
        subs: ["Queijo Cottage (85g)", "Creme de Ricota Light (50g)", "Queijo Muçarela (20g)", "Queijo Minas Frescal Orgânico (30g)", "Iogurte Natural Desnatado (215g)", "Queijo de Coalho (20g)"],
      },
      { main: "Alface, Tomate, Cenoura Ralada à vontade", subs: [] },
      { main: "Fruta (Anexo 1), 2 Porções", subs: [] },
    ],
  },
  {
    id: "jantar1",
    label: "Jantar",
    icon: "🌙",
    suggestion: "Jantar Nordestino Tradicional",
    items: [
      {
        main: "Cuscuz de Milho Cozido (110g)",
        subs: ["Macaxeira Cozida (95g)", "Inhame Cozido (120g)", "Batata Inglesa Cozida (235g)", "Abóbora Cozida (255g)", "Batata Doce Cozida (160g)", "Arroz Branco Cozido (95g)"],
      },
      {
        main: "Carne Bovina Moída Patinho Refogado (150g)",
        subs: ["Peito de Frango Sem Pele Grelhado (150g)", "Carne Bovina Magra (110g)", "Atum Sólido ao Natural (180g)", "Peixe Assado/Grelhado (210g)", "Lombo de Porco Assado (115g)", "Bife de Fígado Grelhado (105g)"],
      },
      { main: "Legumes e Verduras (Anexo 2), 1 Porção (150g)", subs: [] },
    ],
  },
  {
    id: "jantar2",
    label: "Jantar (Op. 2)",
    icon: "🍔",
    suggestion: "Hambúrguer Caseiro",
    items: [
      { main: "Pão Francês, 1 Unidade (50g)", subs: [] },
      {
        main: "Carne Bovina Moída Patinho Refogado (130g)",
        subs: ["Peito de Frango Cru (175g)", "Peito de Frango Grelhado (130g)", "Carne Bovina Crua Magra (160g)"],
      },
      {
        main: "Queijo Muçarela, 1 Fatia (20g)",
        subs: ["Requeijão Cremoso Light (30g)", "Queijo de Coalho (15g)", "Queijo Minas Frescal Orgânico (25g)", "Queijo Cottage (70g)"],
      },
      { main: "Alface, Tomate e Cebola à vontade", subs: [] },
    ],
  },
];

const goals = [
  {
    category: "Alimentação",
    icon: "🥗",
    frequency: "diária",
    items: ["2 a 3 porções de vegetais por dia", "2 a 3 porções de frutas por dia", "Cozinhar mais em casa", "Comer sem distrações"],
  },
  {
    category: "Exercícios",
    icon: "💪",
    frequency: "semanal",
    items: ["Mínimo 8 mil passos por dia", "Musculação 3 a 6 vezes por semana"],
  },
  {
    category: "Sono",
    icon: "😴",
    frequency: "diária",
    items: ["Luz do sol ao acordar", "Sem celular 1h antes de dormir", "Sem café após 17h", "Luzes apagadas 2h antes de deitar"],
  },
  {
    category: "Hidratação",
    icon: "💧",
    frequency: "diária",
    items: ["Mínimo 2.5L de água por dia", "Priorizar frutas com bastante água"],
  },
  {
    category: "Estresse",
    icon: "🧘",
    frequency: "diária",
    items: ["Reservar tempo em local tranquilo", "Caminhada apreciando a paisagem", "Distanciar-se das redes sociais"],
  },
];

const supplements = [
  {
    name: "Whey Protein Concentrado",
    dosage: "Conforme prescrição",
    timing: "Conforme prescrição",
    note: "Procurar com 2g a 6g de carboidrato por porção. Fugir de +10g de carb.",
    brands: "Growth, Integralmedica, Max Titanium, Probiótica, Black Skull",
  },
  {
    name: "Creatina Monoidratada",
    dosage: "5g / dia",
    timing: "Qualquer horário",
    note: "Tomar todos os dias, inclusive dias sem treino.",
    brands: "Growth, Max Titanium, Vitafor, Integralmedica",
  },
  {
    name: "Cafeína",
    dosage: "1 cápsula de 210mg",
    timing: "40 a 60 min antes do exercício",
    note: "Máximo 3x por semana. Evitar após as 16h. Evitar se ansioso(a).",
    brands: "Growth, Max Titanium, Integral Médica, New Millen",
  },
];

const fruits = [
  { name: "Abacaxi", portion: "2 fatias médias (150g)", vitC: true, lowCal: true },
  { name: "Acerola", portion: "21 unidades (250g)", vitC: true, lowCal: true },
  { name: "Açaí (polpa)", portion: "½ copo médio (150g)", vitC: false, lowCal: false },
  { name: "Banana", portion: "1 unidade média (70g)", vitC: false, lowCal: false },
  { name: "Caju", portion: "2 unidades médias (185g)", vitC: true, lowCal: true },
  { name: "Goiaba", portion: "1 unidade média (130g)", vitC: true, lowCal: false },
  { name: "Kiwi", portion: "2 unidades médias (150g)", vitC: true, lowCal: true },
  { name: "Laranja", portion: "1 unidade média (180g)", vitC: true, lowCal: true },
  { name: "Maçã", portion: "1 unidade média (130g)", vitC: false, lowCal: true },
  { name: "Mamão Formosa", portion: "1 fatia média (170g)", vitC: true, lowCal: true },
  { name: "Mamão Papaia", portion: "½ unidade (150g)", vitC: true, lowCal: true },
  { name: "Manga", portion: "1 unidade média (140g)", vitC: true, lowCal: false },
  { name: "Melancia", portion: "1½ fatias (300g)", vitC: false, lowCal: true },
  { name: "Melão", portion: "½ unidade média (300g)", vitC: false, lowCal: true },
  { name: "Morango", portion: "10 unidades (200g)", vitC: true, lowCal: true },
  { name: "Pêra", portion: "1 unidade (110g)", vitC: false, lowCal: true },
  { name: "Tangerina", portion: "1 unidade média (135g)", vitC: true, lowCal: true },
  { name: "Amora", portion: "50 unidades (200g)", vitC: false, lowCal: true },
];

function MealCard({ item, index }) {
  const [open, setOpen] = useState(false);
  const hasSubs = item.subs.length > 0;

  return (
    <div style={{
      background: BRAND.white,
      borderRadius: 12,
      border: `1px solid ${BRAND.grayMid}`,
      overflow: "hidden",
      transition: "box-shadow 0.2s",
    }}>
      <button
        onClick={() => hasSubs && setOpen(!open)}
        style={{
          width: "100%",
          display: "flex",
          alignItems: "center",
          justifyContent: "space-between",
          padding: "14px 16px",
          background: "transparent",
          border: "none",
          cursor: hasSubs ? "pointer" : "default",
          gap: 12,
          textAlign: "left",
          fontFamily: "inherit",
        }}
      >
        <div style={{ display: "flex", alignItems: "center", gap: 10, flex: 1 }}>
          <span style={{
            width: 28, height: 28, borderRadius: 8,
            background: BRAND.redLight, color: BRAND.red,
            display: "flex", alignItems: "center", justifyContent: "center",
            fontSize: 13, fontWeight: 700, flexShrink: 0,
          }}>{index + 1}</span>
          <span style={{ fontSize: 14, color: BRAND.charcoal, fontWeight: 500, lineHeight: 1.4 }}>
            {item.main}
          </span>
        </div>
        {hasSubs && (
          <span style={{
            fontSize: 11, color: BRAND.red, fontWeight: 600,
            background: BRAND.redLight, padding: "4px 8px", borderRadius: 6,
            whiteSpace: "nowrap", flexShrink: 0,
            transform: open ? "none" : "none",
          }}>
            {open ? "fechar" : `${item.subs.length} opções`}
          </span>
        )}
      </button>
      {open && (
        <div style={{
          padding: "0 16px 14px 54px",
          display: "flex", flexDirection: "column", gap: 6,
        }}>
          <div style={{ fontSize: 10, textTransform: "uppercase", letterSpacing: 1.2, color: BRAND.gray, fontWeight: 600, marginBottom: 2 }}>
            Substituições equivalentes
          </div>
          {item.subs.map((sub, i) => (
            <div key={i} style={{
              fontSize: 13, color: BRAND.charcoal, padding: "6px 10px",
              background: BRAND.grayLight, borderRadius: 6,
              display: "flex", alignItems: "center", gap: 8,
            }}>
              <span style={{ color: BRAND.gray }}>↳</span> {sub}
            </div>
          ))}
        </div>
      )}
    </div>
  );
}

function FruitBadge({ fruit }) {
  return (
    <div style={{
      padding: "8px 12px", borderRadius: 10,
      background: BRAND.white, border: `1px solid ${BRAND.grayMid}`,
      display: "flex", flexDirection: "column", gap: 4,
      position: "relative", overflow: "hidden",
    }}>
      <div style={{ display: "flex", gap: 4, position: "absolute", top: 6, right: 6 }}>
        {fruit.vitC && <span style={{ fontSize: 8, background: "#FEF3C7", color: "#92400E", padding: "2px 5px", borderRadius: 4, fontWeight: 600 }}>Vit C</span>}
        {fruit.lowCal && <span style={{ fontSize: 8, background: "#DCFCE7", color: "#166534", padding: "2px 5px", borderRadius: 4, fontWeight: 600 }}>Low Cal</span>}
      </div>
      <span style={{ fontSize: 14, fontWeight: 600, color: BRAND.charcoal }}>{fruit.name}</span>
      <span style={{ fontSize: 12, color: BRAND.gray }}>{fruit.portion}</span>
    </div>
  );
}

export default function App() {
  const [activeTab, setActiveTab] = useState("refeicoes");
  const [activeMeal, setActiveMeal] = useState("cafe");
  const [checkedGoals, setCheckedGoals] = useState({});

  const toggleGoal = (cat, idx) => {
    const key = `${cat}-${idx}`;
    setCheckedGoals(prev => ({ ...prev, [key]: !prev[key] }));
  };

  const currentMeal = meals.find(m => m.id === activeMeal);

  const tabs = [
    { id: "refeicoes", label: "Refeições", icon: "🍴" },
    { id: "metas", label: "Metas", icon: "🎯" },
    { id: "suplementos", label: "Suplementos", icon: "💊" },
    { id: "frutas", label: "Frutas", icon: "🍎" },
  ];

  return (
    <div style={{
      fontFamily: "'DM Sans', 'Helvetica Neue', sans-serif",
      background: "#FAFAFA",
      minHeight: "100vh",
      color: BRAND.charcoal,
    }}>
      <link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700&family=Playfair+Display:wght@700;800&display=swap" rel="stylesheet" />

      {/* Header */}
      <div style={{
        background: BRAND.charcoal,
        padding: "28px 20px 20px",
        position: "relative",
        overflow: "hidden",
      }}>
        <div style={{
          position: "absolute", top: -40, right: -40,
          width: 200, height: 200, borderRadius: "50%",
          background: BRAND.red, opacity: 0.08,
        }} />
        <div style={{
          position: "absolute", bottom: -60, left: -30,
          width: 160, height: 160, borderRadius: "50%",
          background: BRAND.red, opacity: 0.05,
        }} />

        <div style={{ display: "flex", alignItems: "center", gap: 12, marginBottom: 16, position: "relative" }}>
          <div style={{
            width: 42, height: 42, borderRadius: 10,
            background: BRAND.red, display: "flex",
            alignItems: "center", justifyContent: "center",
            fontSize: 20, fontWeight: 800, color: BRAND.white,
            fontFamily: "'Playfair Display', serif",
          }}>G</div>
          <div>
            <div style={{ fontSize: 17, fontWeight: 700, color: BRAND.white, letterSpacing: -0.3 }}>
              Guilherme Carvalho
            </div>
            <div style={{ fontSize: 10, color: "rgba(255,255,255,0.5)", letterSpacing: 3, textTransform: "uppercase", fontWeight: 500 }}>
              Nutrição Inteligente
            </div>
          </div>
        </div>

        <div style={{ position: "relative" }}>
          <div style={{ fontSize: 13, color: "rgba(255,255,255,0.4)", fontWeight: 500 }}>
            Protocolo alimentar para
          </div>
          <div style={{
            fontSize: 26, fontWeight: 800, color: BRAND.white,
            fontFamily: "'Playfair Display', serif",
            lineHeight: 1.2, marginTop: 4,
          }}>
            João Pedro do Nascimento
          </div>
          <div style={{
            display: "inline-flex", alignItems: "center", gap: 6,
            marginTop: 10, padding: "6px 12px", borderRadius: 20,
            background: "rgba(212,32,39,0.15)", border: "1px solid rgba(212,32,39,0.25)",
          }}>
            <span style={{ fontSize: 14 }}>🏆</span>
            <span style={{ fontSize: 12, color: BRAND.red, fontWeight: 600 }}>
              Objetivo: Meia Maratona
            </span>
          </div>
        </div>
      </div>

      {/* Main Tabs */}
      <div style={{
        display: "flex", gap: 0, padding: "0",
        background: BRAND.white,
        borderBottom: `1px solid ${BRAND.grayMid}`,
        position: "sticky", top: 0, zIndex: 10,
      }}>
        {tabs.map(tab => (
          <button
            key={tab.id}
            onClick={() => setActiveTab(tab.id)}
            style={{
              flex: 1, padding: "12px 4px", border: "none",
              background: activeTab === tab.id ? BRAND.white : "transparent",
              borderBottom: activeTab === tab.id ? `2.5px solid ${BRAND.red}` : "2.5px solid transparent",
              cursor: "pointer",
              display: "flex", flexDirection: "column", alignItems: "center", gap: 2,
              transition: "all 0.2s",
              fontFamily: "inherit",
            }}
          >
            <span style={{ fontSize: 16 }}>{tab.icon}</span>
            <span style={{
              fontSize: 11, fontWeight: activeTab === tab.id ? 700 : 500,
              color: activeTab === tab.id ? BRAND.red : BRAND.gray,
            }}>{tab.label}</span>
          </button>
        ))}
      </div>

      {/* Content */}
      <div style={{ padding: "16px", maxWidth: 600, margin: "0 auto" }}>

        {/* REFEIÇÕES */}
        {activeTab === "refeicoes" && (
          <>
            {/* Meal selector pills */}
            <div style={{
              display: "flex", gap: 6, overflowX: "auto",
              paddingBottom: 12, marginBottom: 8,
              scrollbarWidth: "none",
            }}>
              {meals.map(meal => (
                <button
                  key={meal.id}
                  onClick={() => setActiveMeal(meal.id)}
                  style={{
                    padding: "8px 14px", borderRadius: 20,
                    border: activeMeal === meal.id ? `2px solid ${BRAND.red}` : `1px solid ${BRAND.grayMid}`,
                    background: activeMeal === meal.id ? BRAND.redLight : BRAND.white,
                    cursor: "pointer",
                    whiteSpace: "nowrap",
                    fontSize: 12, fontWeight: activeMeal === meal.id ? 700 : 500,
                    color: activeMeal === meal.id ? BRAND.red : BRAND.gray,
                    display: "flex", alignItems: "center", gap: 6,
                    transition: "all 0.2s",
                    fontFamily: "inherit",
                  }}
                >
                  <span>{meal.icon}</span>
                  {meal.label}
                </button>
              ))}
            </div>

            {/* Suggestion banner */}
            <div style={{
              background: `linear-gradient(135deg, ${BRAND.red}, ${BRAND.redDark})`,
              borderRadius: 12, padding: "14px 16px",
              marginBottom: 16, display: "flex", alignItems: "center", gap: 12,
            }}>
              <span style={{ fontSize: 28 }}>👨‍🍳</span>
              <div>
                <div style={{ fontSize: 10, color: "rgba(255,255,255,0.6)", fontWeight: 600, textTransform: "uppercase", letterSpacing: 1 }}>
                  Sugestão de preparo
                </div>
                <div style={{ fontSize: 15, color: BRAND.white, fontWeight: 700, marginTop: 2 }}>
                  {currentMeal.suggestion}
                </div>
              </div>
            </div>

            {/* Meal items */}
            <div style={{ display: "flex", flexDirection: "column", gap: 8 }}>
              {currentMeal.items.map((item, i) => (
                <MealCard key={i} item={item} index={i} />
              ))}
            </div>

            <div style={{
              marginTop: 16, padding: "12px 16px",
              background: "#FFF7ED", borderRadius: 10,
              border: "1px solid #FED7AA",
              fontSize: 12, color: "#92400E", lineHeight: 1.5,
            }}>
              💡 <strong>Dica:</strong> Toque em "opções" para ver as substituições equivalentes de cada alimento. Você pode trocar livremente dentro do mesmo grupo.
            </div>
          </>
        )}

        {/* METAS */}
        {activeTab === "metas" && (
          <div style={{ display: "flex", flexDirection: "column", gap: 16 }}>
            <div style={{
              textAlign: "center", padding: "16px",
              background: `linear-gradient(135deg, ${BRAND.red}, ${BRAND.redDark})`,
              borderRadius: 14,
            }}>
              <div style={{ fontSize: 32 }}>🏆</div>
              <div style={{ fontSize: 20, fontWeight: 800, color: BRAND.white, fontFamily: "'Playfair Display', serif", marginTop: 6 }}>
                Meia Maratona
              </div>
              <div style={{ fontSize: 12, color: "rgba(255,255,255,0.6)", marginTop: 4 }}>Objetivo principal</div>
            </div>

            {goals.map((goal) => (
              <div key={goal.category} style={{
                background: BRAND.white, borderRadius: 12,
                border: `1px solid ${BRAND.grayMid}`, overflow: "hidden",
              }}>
                <div style={{
                  padding: "14px 16px",
                  display: "flex", alignItems: "center", justifyContent: "space-between",
                  borderBottom: `1px solid ${BRAND.grayMid}`,
                }}>
                  <div style={{ display: "flex", alignItems: "center", gap: 10 }}>
                    <span style={{ fontSize: 22 }}>{goal.icon}</span>
                    <span style={{ fontSize: 15, fontWeight: 700, color: BRAND.charcoal }}>{goal.category}</span>
                  </div>
                  <span style={{
                    fontSize: 10, color: BRAND.gray, fontWeight: 600,
                    background: BRAND.grayLight, padding: "3px 8px", borderRadius: 4,
                    textTransform: "uppercase", letterSpacing: 0.5,
                  }}>{goal.frequency}</span>
                </div>
                <div style={{ padding: "10px 16px", display: "flex", flexDirection: "column", gap: 2 }}>
                  {goal.items.map((item, idx) => {
                    const key = `${goal.category}-${idx}`;
                    const checked = checkedGoals[key];
                    return (
                      <button
                        key={idx}
                        onClick={() => toggleGoal(goal.category, idx)}
                        style={{
                          display: "flex", alignItems: "center", gap: 10,
                          padding: "10px 4px", background: "transparent",
                          border: "none", cursor: "pointer", textAlign: "left",
                          fontFamily: "inherit", width: "100%",
                        }}
                      >
                        <div style={{
                          width: 22, height: 22, borderRadius: 6, flexShrink: 0,
                          border: checked ? `2px solid ${BRAND.red}` : `2px solid ${BRAND.grayMid}`,
                          background: checked ? BRAND.red : "transparent",
                          display: "flex", alignItems: "center", justifyContent: "center",
                          transition: "all 0.2s",
                        }}>
                          {checked && <span style={{ color: BRAND.white, fontSize: 13, fontWeight: 700 }}>✓</span>}
                        </div>
                        <span style={{
                          fontSize: 13, color: checked ? BRAND.gray : BRAND.charcoal,
                          textDecoration: checked ? "line-through" : "none",
                          fontWeight: 500, transition: "all 0.2s",
                        }}>{item}</span>
                      </button>
                    );
                  })}
                </div>
              </div>
            ))}
          </div>
        )}

        {/* SUPLEMENTOS */}
        {activeTab === "suplementos" && (
          <div style={{ display: "flex", flexDirection: "column", gap: 12 }}>
            {supplements.map((sup) => (
              <div key={sup.name} style={{
                background: BRAND.white, borderRadius: 14,
                border: `1px solid ${BRAND.grayMid}`,
                overflow: "hidden",
              }}>
                <div style={{
                  padding: "16px",
                  borderBottom: `1px solid ${BRAND.grayMid}`,
                  display: "flex", alignItems: "center", gap: 12,
                }}>
                  <div style={{
                    width: 44, height: 44, borderRadius: 12,
                    background: BRAND.redLight, display: "flex",
                    alignItems: "center", justifyContent: "center",
                    fontSize: 22,
                  }}>💊</div>
                  <div>
                    <div style={{ fontSize: 16, fontWeight: 700, color: BRAND.charcoal }}>{sup.name}</div>
                    <div style={{ fontSize: 12, color: BRAND.gray }}>{sup.brands}</div>
                  </div>
                </div>
                <div style={{ padding: "14px 16px", display: "flex", flexDirection: "column", gap: 10 }}>
                  <div style={{ display: "flex", gap: 8 }}>
                    <div style={{
                      flex: 1, padding: "10px 12px", borderRadius: 8,
                      background: BRAND.grayLight,
                    }}>
                      <div style={{ fontSize: 10, color: BRAND.gray, fontWeight: 600, textTransform: "uppercase", letterSpacing: 0.5 }}>Dosagem</div>
                      <div style={{ fontSize: 14, fontWeight: 600, color: BRAND.charcoal, marginTop: 2 }}>{sup.dosage}</div>
                    </div>
                    <div style={{
                      flex: 1, padding: "10px 12px", borderRadius: 8,
                      background: BRAND.grayLight,
                    }}>
                      <div style={{ fontSize: 10, color: BRAND.gray, fontWeight: 600, textTransform: "uppercase", letterSpacing: 0.5 }}>Quando</div>
                      <div style={{ fontSize: 14, fontWeight: 600, color: BRAND.charcoal, marginTop: 2 }}>{sup.timing}</div>
                    </div>
                  </div>
                  <div style={{
                    padding: "10px 12px", borderRadius: 8,
                    background: "#FFF7ED", border: "1px solid #FED7AA",
                    fontSize: 12, color: "#92400E", lineHeight: 1.5,
                  }}>
                    ⚠️ {sup.note}
                  </div>
                </div>
              </div>
            ))}
          </div>
        )}

        {/* FRUTAS */}
        {activeTab === "frutas" && (
          <>
            <div style={{
              padding: "12px 16px", borderRadius: 10,
              background: BRAND.redLight, border: `1px solid ${BRAND.red}20`,
              marginBottom: 14, fontSize: 13, color: BRAND.charcoal, lineHeight: 1.5,
            }}>
              Cada porção equivale a aproximadamente <strong>80 kcal</strong>. Escolha variando as opções diariamente.
            </div>

            <div style={{ display: "flex", gap: 8, marginBottom: 14, flexWrap: "wrap" }}>
              <span style={{ fontSize: 11, background: "#FEF3C7", color: "#92400E", padding: "4px 10px", borderRadius: 6, fontWeight: 600 }}>🟡 Rica em Vitamina C</span>
              <span style={{ fontSize: 11, background: "#DCFCE7", color: "#166534", padding: "4px 10px", borderRadius: 6, fontWeight: 600 }}>🟢 Baixa caloria</span>
            </div>

            <div style={{
              display: "grid",
              gridTemplateColumns: "repeat(auto-fill, minmax(150px, 1fr))",
              gap: 8,
            }}>
              {fruits.map(f => <FruitBadge key={f.name} fruit={f} />)}
            </div>
          </>
        )}
      </div>

      {/* Footer */}
      <div style={{
        padding: "24px 20px", marginTop: 24,
        textAlign: "center", borderTop: `1px solid ${BRAND.grayMid}`,
        background: BRAND.white,
      }}>
        <div style={{ fontSize: 11, color: BRAND.gray }}>
          CRN 22286 · Atualizado em 14/09/2026
        </div>
        <div style={{ fontSize: 11, color: BRAND.gray, marginTop: 4 }}>
          guilhermeprofessor.nutri@gmail.com · (79) 9 9649-4208
        </div>
      </div>
    </div>
  );
}
