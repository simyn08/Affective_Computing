# Affective Computing | 감성 컴퓨팅

> **사용자의 감정·표정 등을 인식하고, 감정적 맥락을 이해하여 상황에 적절하게 반응하도록 설계된 인간 중심 AI 기술**

감성 컴퓨팅(Affective Computing)은 인간의 **감정 상태를 추정하고 해석하여 이에 기반한 반응을 생성하는 AI 기술 및 연구 분야**입니다.

감정이 인간의 의사소통과 상호작용 전반에 중요한 영향을 미친다는 점에서 출발하며, AI가 사용자의 감정 정보를 이해하고 이에 적절하게 대응함으로써 보다 자연스럽고 만족도 높은 인간–AI 상호작용을 구현하는 것을 목표로 합니다.

---

## 1. What is Affective Computing?

감성 컴퓨팅은 다음과 같은 다양한 정보를 활용하여 사용자의 감정 상태를 추정합니다.

| 감정 정보 | 주요 분석 대상 |
|---|---|
| 😊 Facial Expression | 얼굴 표정, 시선, 얼굴 움직임 |
| 🎙️ Voice | 음성 톤, 높낮이, 속도, 강도 |
| ❤️ Physiological Signals | 심박, 피부전도도 등 생체 신호 |
| 📝 Text | 문장, 단어, 표현에 나타나는 감정 |
| 🧍 Behavior | 행동 패턴, 몸짓, 상호작용 방식 |

초기 감성 컴퓨팅 연구는 주로 **얼굴 표정과 음성 분석**을 중심으로 발전했습니다.

최근에는 생체 신호, 행동 패턴, 텍스트 감정 분석 등을 함께 활용하는 **멀티모달 감정 인식(Multimodal Emotion Recognition)** 방식으로 확장되고 있습니다.

---

## 2. Core Components

감성 컴퓨팅은 크게 다음의 세 단계로 구성할 수 있습니다.

### ① Emotion Recognition | 감정 인식

사용자의 감정과 관련된 다양한 신호를 수집하는 단계입니다.

**Examples**
- Facial Expression
- Voice Tone
- Heart Rate
- Physiological Signals
- Text
- Behavioral Patterns

↓

### ② Emotion Interpretation | 감정 해석

수집된 정보를 AI가 분석하여 사용자의 감정 상태를 추정하는 단계입니다.

**Examples**
- Happiness
- Sadness
- Anger
- Anxiety
- Confusion
- Interest
- Engagement

↓

### ③ Emotion-based Response | 감정 기반 반응

분석된 감정 상태를 바탕으로 AI 시스템이 적절한 반응을 생성합니다.

**Examples**
- 대화 톤 조정
- 설명 방식 변경
- 맞춤형 피드백 제공
- 상호작용 방식 조정
- 콘텐츠 추천

---

## 3. Affective Computing Process

감성 컴퓨팅의 기본적인 처리 흐름은 다음과 같이 정리할 수 있습니다.

```text
User
  ↓
Emotion-related Signals
  ↓
┌─────────────────────────────┐
│ Facial Expression           │
│ Voice                       │
│ Text                        │
│ Physiological Signals       │
│ Behavioral Patterns         │
└─────────────────────────────┘
  ↓
Emotion Recognition
  ↓
Emotion Interpretation
  ↓
Emotion State Estimation
  ↓
Adaptive AI Response
  ↓
Human–AI Interaction
