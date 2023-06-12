# Music Generation_LSTM
RNN의 한종류인 LSTM을 이용한 음악 생성 


## 🖥️ 프로젝트 소개
전공했던 음악 관련 산업인 작곡 AI 관련 분야에 흥미를 느껴 개인 공부.
Kaggle을 통해 공유된 Classical Midi 파일을 이용
그 중 서유럽(스페인)의 Albeniz, 중앙유럽(오스트리아)Mozart, 동유럽(러시아)차이코프스키의 곡들을 학습데이터로 이용하여 작곡 AI 모델 설계
<br>

## 🕰️ 개발 기간
* 22.06.05-22.06.12

### 🧑‍🤝‍🧑 맴버구성
- 남현수

### ⚙️ 개발 환경
- **python3**:
    - `lilypond`
    - `Music21`

## 📌 결론
- Classical Music Midi(Mozart & Albeniz & tschai)의 음악을 학습데이터로 이용하여 모델을 학습 시킨 후 기존에 존재하지 않던 10곡의 노래를 만들 수 있다. 

- 여러 악기가 포함되어 있는 Lakh midiset를 input 값으로 두고 모델을 작동시켜봤으나 만족할만한 결과물을 얻지 못했다. 이것과 관련하여 깃허브에 공유된 코드들이나 논문을 참고해봐야 할 것 같다.
    - **Lakh MIDI Dataset Clean(A collection of large number of MIDI files)**
    - 176,581개의 고유한 MIDI 파일 모음, 그 중 45,129개가 Million Song 데이터 세트의 항목과 일치하고 정렬
    - Clean MIDI: 일부 내 논문에서 사용된 것처럼 아티스트와 제목을 나타내는 파일 이름이 있는 MIDI 파일의 하위 집합

- 하나의 이미지를 제공했을 때 그 이미지를 인식(인물의 표정이나 인물간의 상황, 텍스트 분석, 이미지의 색감)하여 어울리는 듯한 음악을 작곡, 제공해줄 수 있는 모델을 만들어 보고 싶다는 생각을 하였다.