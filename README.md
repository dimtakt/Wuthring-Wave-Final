<div align=center>

## DX11 3D Final : 명조

<img width="700" src="https://img.sdtr.dev/images/2026-09-06_220328/portfolio04.png">

<table>
  <tr>
    <td>인원</td>
    <td>7인 (Framework, <strong>UI</strong>, Player, Monster, Map, Effect, Shader)</td>
  </tr>
  <tr>
    <td>모작 대상</td>
    <td>
      <a href="https://store.steampowered.com/app/3513350/Wuthering_Waves/">명조</a>
    </td>
  </tr>
  <tr>
    <td>개발기간</td>
    <td>25. 10. 1. ~ 12. 15. (76일)</td>
  </tr>
  <tr>
    <td>사용 언어</td>
    <td><code>C++</code>, <code>HLSL</code></td>
  </tr>
  <tr>
    <td>사용 라이브러리</td>
    <td>
      <code>DirectX 11</code>,
      <code>FMOD</code>,
      <a href="https://github.com/ocornut/imgui"><code>ImGui</code></a>,
      <a href="https://github.com/assimp/assimp"><code>Assimp</code></a>,
      <a href="https://github.com/NVIDIA-Omniverse/PhysX"><code>PhysX</code></a>,
      <a href="https://github.com/freetype/freetype"><code>FreeType</code></a>,
      <a href="https://github.com/nlohmann/json"><code>Nlohmann JSON</code></a>
    </td>
  </tr>
</table>

<hr>

### 팀원 목록

| 이름 | 역할 | 설명 |
| :---: | :--- | :--- |
| **박지호(팀장)** | **MainFramework** | 메인 프레임워크, 카메라, 최적화, 레벨 디자인, 천국 맵 배치|
| **김정훈** | **Shader** | 디퍼드 렌더링 파이프라인, SFX |
| **노영훈** | **Player / Animation** | 플레이어 상태 제어, 애니메이션 제어 |
| **임은비** | **Effects** | 전투 및 환경 Effect |
| **이진호** | **AI / Monster** | 몬스터 전투 AI, NPC |
| **김기훈** | **UI System** | UI 인터페이스, 미니게임, 스크립트 |
| **신우혁** | **Map** | 맵 에디터, 1Stage 배치 |

<hr>

<details>
  <summary>Highlight & Flow Details</summary>

### 게임 플레이 하이라이트

<table>
  <tr>
    <td align="center" width="50%">
      <h3>레비아탄 컷씬</h3>
      <img src="./Styles/LeviatanCutScene.webp" width="100%">
    </td>
    <td align="center" width="50%">
      <h3>레비아탄 전투 (QTE)</h3>
      <img src="./Styles/LeviatanQTE2.webp" width="100%">
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <h3>코로사우로스 전투</h3>
      <img src="./Styles/Corosaurus.webp" width="100%">
    </td>
    <td align="center" width="50%">
      <h3>거짓된 신왕 전투</h3>
      <img src="./Styles/LieKing.webp" width="100%">
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <h3>로그인 화면 </h3>
      <img src="./Styles/EnvMap.webp" width="100%">
    </td>
    <td align="center" width="50%">
      <h3>갓 레이</h3>
      <img src="./Styles/Ray0.webp" width="100%">
    </td>
  </tr>
  
</table>

### 구현 요약

<img src="https://github.com/PJH1998/Wuthring-Wave-Final/blob/main/Styles/FlowChart-Prototype.png" width="100%">

</details>




