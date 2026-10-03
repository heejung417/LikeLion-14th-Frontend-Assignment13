# 프로필 카드 (Figma → React + Tailwind)

피그마 종합실습 때 만든 프로필 카드 CodeTea 플러그인으로 뽑아서 조금 고쳐봤어용

## Figma → Tailwind

- 카드 Vertical Auto Layout → flex flex-col
- 카드 W 700 / Padding 50 / Gap 60 / Radius 30 → w-[700px] p-[50px] gap-[60px] rounded-[30px]
- 프로필 Horizontal + 가운데 정렬, Gap 50 → flex items-center gap-[50px]
- 이름이랑 직무 Vertical, Gap 20 → flex flex-col gap-5
- 태그 Wrap, Gap 30 → flex flex-wrap gap-[30px] (자리 없으면 다음 줄로 넘어감)
- 태그 Hug / Padding 40 → shrink-0 px-10 
- Fill Container → self-stretch
- 버튼 오른쪽 정렬 → 감싸는 div에 flex flex-col items-end


