1. TTF가 뭔가
   ↓
2. hb-shape main()
   ↓
3. hb_shape()
   ↓
4. HarfBuzz 내부 shaping
   ↓
5. glyph ID + position
   ↓
6. FreeType
   ↓
7. glyph outline
   ↓
8. rasterization
   ↓
9. Skia / GPU
   ↓
화면