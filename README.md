# 🚀 PicoArt v5 - 초간단 배포 (수정 불필요!)

## ✅ 자동 설정 완료!
**수동으로 URL 수정할 필요 없어요!** 코드가 자동으로 감지합니다.

---

## 📁 폴더 구조 (그대로 업로드)

```
picoart-final-deploy/
├── index.html
├── api/
│   ├── convert.js
│   └── status.js
├── artworks/
│   └── vangogh/
│       ├── 01_starry_night.jpg
│       ├── 02_sunflowers.jpg
│       ├── 03_self_portrait.jpg
│       ├── 04_bedroom.jpg
│       ├── 05_cafe_terrace.jpg
│       ├── 06_irises.jpg
│       └── 07_wheat_field.jpg
└── vercel.json
```

---

## 🚀 배포 2단계

### 1️⃣ GitHub 업로드
```
1. https://github.com/new
2. Repository name: picoart-vangogh
3. Public 선택
4. "Create repository"
5. "uploading an existing file" 클릭
6. 압축 푼 폴더의 모든 파일 드래그 앤 드롭
   ⚠️ 중요: artworks 폴더 포함!
7. "Commit changes"
```

### 2️⃣ Vercel 배포
```
1. https://vercel.com/new
2. Import Git Repository
3. picoart-vangogh 선택
4. Deploy 클릭 (아무것도 수정하지 말기!)
5. 1-2분 대기
6. 완료! ✨
```

---

## ✅ 테스트

1. **시크릿 창**에서 배포된 URL 접속
2. **F12** → Console 열기
3. Replicate API 토큰 입력
4. **Van Gogh** 선택
5. 사진 업로드
6. **변환 시작** 클릭
7. Console 확인:
   ```
   🌐 Using artwork base URL: /artworks/vangogh
   🎨 ===== AI Auto-Matching =====
   🖼️ Selected: "별이 빛나는 밤"
   ```

---

## 🎯 핵심 기능

- ✅ AI가 7작품 중 자동 선택
- ✅ 매칭된 명화 표시
- ✅ URL 자동 감지 (수정 불필요!)
- ✅ 완전한 명화 DB 포함

---

## 🔍 문제 해결

### 이미지 404 에러?
→ artworks 폴더를 GitHub에 업로드했는지 확인

### 변환 실패?
→ Replicate API 토큰과 크레딧 확인

---

**끝! 이제 그냥 업로드만 하면 됩니다! 🎉**
