# ECoG_InnerSpeechSynthesis

<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <title>오디오 테이블 페이지</title>
  <style>
    h1 { text-align: center; font-size: 2em; }
    p.authors { text-align: center; font-style: italic; font-size: 1.5em; margin-bottom: 20px; }
    p.affiliations { text-align: center; font-size: 1em; line-height: 1.2; margin-top: 0; } 
    .table-container { display: flex; justify-content: space-around; margin-bottom: 20px; }
    table { border-collapse: collapse; width: 45%; }
    caption { text-align: center; font-weight: bold; margin-bottom: 10px; font-size: 1.2em; }
    th, td { border: 1px solid black; padding: 8px; text-align: center; }
    audio { width: 200px; }
  </style>
</head>
<body>
  <h1>Feasibility of synthesizing inner speech from ECoG using an autoencoder-based unsupervised learning</h1>
  <p class="authors">Jihun Hwang<sup>a</sup>, Hongsang Lee<sup>b</sup>, Chun Kee Chung<sup>c</sup> and Chang-Hwan Im<sup>a,b,d*</sup></p>
  <p class="affiliations"><sup>a</sup>Department of Electronic Engineering, Hanyang University, Republic of Korea</p>
  <p class="affiliations"><sup>b</sup>Department of Artificial Intelligence, Hanyang University, Republic of Korea</p>
  <p class="affiliations"><sup>c</sup>Neuroscience Research Institute, Seoul National University Medical Research Center, Republic of Korea</p>
  <p class="affiliations"><sup>d</sup>Department of Biomedical Engineering, Hanyang University, Republic of Korea</p>  

  <!-- 첫 번째 테이블 그룹 (P1) -->
  <div class="table-container">
    <table>
      <caption>P1</caption>
      <thead>
        <tr>
          <th>Original</th>
          <th>Prediction</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><audio controls><source src="[/Assets/P1_둘_ori.wav](https://github.com/igonan1igonan2/ECoG_InnerSpeechSynthesis/raw/main/Assets/P1_둘_ori.wav)" type="audio/wav"></audio></td>
          <td><audio controls><source src="https://github.com/igonan1igonan2/ECoG_InnerSpeechSynthesis/raw/main/Assets/P1_둘_pre.wav" type="audio/wav"></audio></td>
        </tr>
        <tr>
          <td><audio controls><source src="https://github.com/igonan1igonan2/ECoG_InnerSpeechSynthesis/raw/main/Assets/P1_숨쉬다_ori.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="https://github.com/igonan1igonan2/ECoG_InnerSpeechSynthesis/raw/main/Assets/P1_숨쉬다_pre.wav" type="audio/wav"></audio></td>
        </tr>
      </tbody>
    </table>
    <table>
      <caption>P2</caption>
      <thead>
        <tr>
          <th>Original</th>
          <th>Prediction</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><audio controls><source src="https://github.com/igonan1igonan2/ECoG_InnerSpeechSynthesis/raw/main/Assets/P2_발_ori.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="https://github.com/igonan1igonan2/ECoG_InnerSpeechSynthesis/raw/main/Assets/P2_발_pre.wav" type="audio/wav"></audio></td>
        </tr>
        <tr>
          <td><audio controls><source src="https://github.com/igonan1igonan2/ECoG_InnerSpeechSynthesis/raw/main/Assets/P2_친구_ori.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="https://github.com/igonan1igonan2/ECoG_InnerSpeechSynthesis/raw/main/Assets/P2_친구_pre.wav" type="audio/wav"></audio></td>
        </tr>
      </tbody>
    </table>
  </div>

  <!-- 아래에 복제 구조 (P2) -->
  <div class="table-container">
    <table>
      <caption>P3</caption>
      <thead>
        <tr>
          <th>Original</th>
          <th>Prediction</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><audio controls><source src="https://github.com/igonan1igonan2/ECoG_InnerSpeechSynthesis/raw/main/Assets/P3_코_ori.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="https://github.com/igonan1igonan2/ECoG_InnerSpeechSynthesis/raw/main/Assets/P3_코_pre.wav" type="audio/wav"></audio></td>
        </tr>
        <tr>
          <td><audio controls><source src="https://github.com/igonan1igonan2/ECoG_InnerSpeechSynthesis/raw/main/Assets/P3_의사_ori.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="https://github.com/igonan1igonan2/ECoG_InnerSpeechSynthesis/raw/main/Assets/P3_의사_pre.wav" type="audio/wav"></audio></td>
        </tr>
      </tbody>
    </table>
    <table>
      <caption>P4</caption>
      <thead>
        <tr>
          <th>Original</th>
          <th>Prediction</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><audio controls><source src="https://github.com/igonan1igonan2/ECoG_InnerSpeechSynthesis/raw/main/Assets/P4_나_ori.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="https://github.com/igonan1igonan2/ECoG_InnerSpeechSynthesis/raw/main/Assets/P4_나_pre.wav" type="audio/wav"></audio></td>
        </tr>
        <tr>
          <td><audio controls><source src="https://github.com/igonan1igonan2/ECoG_InnerSpeechSynthesis/raw/main/Assets/P4_아홉_ori.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="https://github.com/igonan1igonan2/ECoG_InnerSpeechSynthesis/raw/main/Assets/P4_아홉_pre.wav" type="audio/wav"></audio></td>
        </tr>
      </tbody>
    </table>
  </div>
</body>
</html>
