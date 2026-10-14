# STRUCTURE · oddatlier-sample

```
oddatlier-sample/
├─ index.html              단일 파일 (CSS·JS 인라인)
├─ wrangler.toml           name = oddatelier-sample → oddatelier-sample.lgt3232.workers.dev
├─ .assetsignore           img/·문서·index_*.html·미사용 webp 10장 배포 제외
├─ oa-intertight.woff2     영문 (Inter Tight 가변 300–700 · GHEA Helvetica 대체)
├─ oa-pretendard.woff2     한글 (Pretendard 가변 · 사용 글자만 → 글자 추가 시 재생성)
├─ oa-*.webp               사진 (hero·terrace·door = 히어로 크로스페이드 / f* = Plates / d* = Drinks)
├─ favicon.png             벽돌색 O + 잎 점
├─ og-odd.jpg              공유 썸네일 1200×630
├─ img/                    다올 제공 원본 45장 (배포 제외)
└─ CHANGELOG.md / STRUCTURE.md
```

## 섹션 순서
헤더 → 히어로(`#slides`) → `#about`(흰) → `#plates`(회벽 · 9장) → `#drinks`(벽돌 면) → `#pets`(흰 · 규칙) → `#visit`(채널 8칸 `.links` + 지도) → 벽돌 푸터.

## 색 사용 규칙
벽돌 `--brick`은 큰 면(Drinks·푸터·주 버튼), 잎 `--leaf`는 작은 포인트(라벨 점·호버·포커스)만.

## 폰트 재생성
`pyftsubset … --name-IDs='*' --name-languages='*' --name-legacy` (라이선스 보존, LESSONS §24).
