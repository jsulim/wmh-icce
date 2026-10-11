# wmh-paper

IEEE ICCE 2027 투고 원고.
코드와 실험 결과는 별도 저장소 `wmh-compression`에 있다.

## 구성

| 파일 | 내용 |
|---|---|
| `main.tex` | 본문 (IEEEtran conference, 4쪽) |
| `refs.bib` | 참고문헌 |
| `figures/` | 그림 (PDF 벡터 우선) |

## 필요한 그림

| 파일 | 내용 | 출처 |
|---|---|---|
| `fig1_architecture_bc.pdf` | 폭 축소 vs 깊이 축소 구조 | `wmh_fig1_bc.py` |
| `fig_map_78.pdf` | 환자 #78 작은 병변 지도 | `wmh_lesion_map_colab.py` |

## 쓰는 순서

1. Sec. IV Results — 표가 이미 채워져 있으니 설명만
2. Sec. III Method
3. Sec. I Introduction
4. Sec. V/VI Discussion, Conclusion
5. Abstract

`\todo{...}` 로 표시된 곳만 채우면 된다.
제출 전 `\newcommand{\todo}[1]{}` 로 바꾸면 빨간 메모가 전부 사라진다.

## Overleaf 동기화

Menu → GitHub → Pull / Push. **자동이 아니라 버튼을 눌러야 한다.**

> 한 번에 한 곳에서만 쓴다. 자리를 옮기기 전에 항상 푸시·동기화한다.

- VSCode → Overleaf: `git push` 후 Overleaf에서 Pull
- Overleaf → VSCode: Overleaf에서 Push 후 `git pull`

## 제출 전 점검

- [ ] `\todo` 전부 제거
- [ ] `refs.bib`의 `[DOI 확인]` 2건 (FedASAP, Huang et al. 2025)
- [ ] 저자·소속·이메일
- [ ] 4쪽 이내
- [ ] 그림이 흑백 인쇄에서도 읽히는지
