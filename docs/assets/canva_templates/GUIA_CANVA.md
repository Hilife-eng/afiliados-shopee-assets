# 🎨 Guia Rápido: Criar no Canva (15-20 min)

## 📁 Arquivos Gerados
- `canva_design_spec.json` — Especificação completa (cores, fontes, layout, componentes)
- `canva_bulk_create.csv` — Dados para Bulk Create do Canva
- Imagens fonte em `../story_v2/` (ou use as originais)

---

## ⚡ Passo a Passo no Canva

### 1. Setup Inicial (3 min)
```
• Create a design > Custom size > 1080 x 1920 px
• File > Settings > Show margins > Custom margins
  - Top: 150 | Bottom: 350 | Left: 60 | Right: 60
• Brand Kit > Colors > Add "Cascata Natal":
  - #FF6B35 Laranja | #2ED573 Verde | #A55EEA Roxo
  - #2E86DE Azul | #FFD700 Dourado
  - Whites: 100%, 80%, 50%, 20% | Blacks: 60%, 40%, 20%
• Text Styles (create all):
  - Display: Montserrat Alternates 64px Bold 1.15 LH -0.02 LS
  - H1: Montserrat Alternates 52px Bold 1.2 LH -0.01 LS
  - H3: Montserrat 32px SemiBold 1.3 LH
  - Body LG: Montserrat 26px Regular 1.4 LH
  - Body: Montserrat 22px Regular 1.5 LH
  - Caption: Montserrat 18px Medium 1.4 LH
  - CTA Badge: Montserrat Alternates 30px ExtraBold 1.2 LH 0.02 LS
```

### 2. Componentes Reutilizáveis (3 min)
```
Badge Preço (Component):
  - Rounded rectangle 12px radius
  - Padding 24x12
  - Text: H3 style
  - Variants: Laranja (🔥), Verde (✅), Azul (⚡), Dourado (🏆)

CTA Badge (Component):
  - Rounded rectangle 28px radius
  - Padding 32x16
  - Text: CTA Badge style
  - BG: Laranja #FF6B35
  - Border: 3px Dourado #FFD700
  - Shadow: 0 4px 12px rgba(0,0,0,0.4)
```

### 3. Criar 5 Páginas (5 min)
```
Duplique a página base 5x:
1. Cena 01 - Gancho (img1, gradient center, mystery look)
2. Cena 02 - Problema (img1, gradient center, desaturated look)
3. Cena 03 - Descoberta (img2, gradient bottom, vibrant look)
4. Cena 04 - Transformação (img1, gradient bottom, glorious look)
5. Cena 05 - Venda (img2, gradient bottom, clean look + CTA Badge)
```

### 4. Bulk Create (2 min)
```
Apps > Bulk Create > Upload CSV > canva_bulk_create.csv
Connect:
  {{headline}} → Text box headline
  {{subtext}} → Text box subtext
  {{specs}} → Text box specs
  {{price}} → Badge Preço component
  {{cta_text}} → CTA Badge component (só cena 5)
  {{watermark}} → Caption text (canto inf dir)
Generate > Review > Create designs
```

### 5. Ajuste Fino + Export (3 min)
```
• Revise cada cena: hierarchy, spacing, safe zones
• Animate: Photo > Animate > "Fade In" ou "Rise" (0.5s)
• Text > Animate: "Typewriter" ou "Fade In" (0.3s delay)
• Audio: Upload música natalina suave > Trim to 25-30s
• Share > Download > MP4 Video (1080p) OU PNG pages
```

---

## 🎬 Timing Sugerido (Total ~25s)
| Cena | Duração | Transição |
|------|---------|-----------|
| 1 Gancho | 3s | Cut → |
| 2 Problema | 3s | Crossfade 0.5s → |
| 3 Descoberta | 6s | Cut → |
| 4 Transformação | 6s | Crossfade 0.5s → |
| 5 Venda | 7s | End |

---

## ✅ Checklist Final
- [ ] Safe zones respeitados (nada cortado no Stories/Reels)
- [ ] Hierarquia visual clara (olho vai: headline → specs → price → CTA)
- [ ] CTA "COMENTE EU QUERO" bem visível na cena 5
- [ ] Watermark sutil (20% opacity) não compete
- [ ] Música não tem copyright (use YouTube Audio Library ou Epidemic Sound)
- [ ] Legendas automáticas ativadas ao postar

---

## 🔗 Link do Afiliado
```
https://s.shopee.com.br/4qHENyXRK7
```
Use no watermark + sticker Link nativo + pinned comment + DM auto (@engajamento)
