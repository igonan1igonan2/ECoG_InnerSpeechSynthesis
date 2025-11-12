# ECoG_InnerSpeechSynthesis
GitHub page for paper "Feasibility of synthesizing inner speech from ECoG using an autoencoder-based unsupervised learning."


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
  <h1>Enhanced Synthesis of Passively Heard Speech from Electrocorticography Signals Using Image-to-Image Spectrogram Translation</h1>
  <p class="authors">Hongsang Lee<sup>1</sup>, Jihun Hwang<sup>2</sup>, Kyungjun Kim<sup>3</sup>, Gyuwon Lee<sup>4</sup>, Chun Kee Chung<sup>5</sup> and Chang-Hwan Im<sup>1,2,3*</sup></p>
  <p class="affiliations"><sup>1</sup>Department of Artificial Intelligence, Hanyang University, Republic of Korea</p>
  <p class="affiliations"><sup>2</sup>Department of Electronic Engineering, Hanyang University, Republic of Korea</p>
  <p class="affiliations"><sup>3</sup>Department of Biomedical Engineering, Hanyang University, Republic of Korea</p>
  <p class="affiliations"><sup>4</sup>Department of Brain and Cognitive Sciences, Seoul National University College of Natural Sciences, Republic of Korea</p>
  <p class="affiliations"><sup>5</sup>Neuroscience Research Institute, Seoul National University Medical Research Center, Republic of Korea</p>
  
  <!-- 첫 번째 테이블 그룹 (P1) -->
  <div class="table-container">
    <table>
      <caption>P1</caption>
      <thead>
        <tr>
          <th>Original</th>
          <th>Initial Synthesis</th>
          <th>Enhanced</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><audio controls><source src="P1/1_original.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="P1/1_initial_synthesis.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="P1/1_pix2pixHD.wav" type="audio/wav"></audio></td>
        </tr>
        <tr>
          <td><audio controls><source src="P1/2_original.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="P1/2_initial_synthesis.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="P1/2_pix2pixHD.wav" type="audio/wav"></audio></td>
        </tr>
        <tr>
          <td><audio controls><source src="P1/3_original.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="P1/3_initial_synthesis.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="P1/3_pix2pixHD.wav" type="audio/wav"></audio></td>
        </tr>
        <tr>
          <td><audio controls><source src="P1/4_original.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="P1/4_initial_synthesis.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="P1/4_pix2pixHD.wav" type="audio/wav"></audio></td>
        </tr>
        <tr>
          <td><audio controls><source src="P1/5_original.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="P1/5_initial_synthesis.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="P1/5_pix2pixHD.wav" type="audio/wav"></audio></td>
        </tr>
      </tbody>
    </table>
    <table>
      <caption>P1</caption>
      <thead>
        <tr>
          <th>Original</th>
          <th>Initial Synthesis</th>
          <th>Enhanced</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><audio controls><source src="P1/6_original.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="P1/6_initial_synthesis.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="P1/6_pix2pixHD.wav" type="audio/wav"></audio></td>
        </tr>
        <tr>
          <td><audio controls><source src="P1/7_original.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="P1/7_initial_synthesis.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="P1/7_pix2pixHD.wav" type="audio/wav"></audio></td>
        </tr>
        <tr>
          <td><audio controls><source src="P1/8_original.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="P1/8_initial_synthesis.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="P1/8_pix2pixHD.wav" type="audio/wav"></audio></td>
        </tr>
        <tr>
          <td><audio controls><source src="P1/9_original.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="P1/9_initial_synthesis.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="P1/9_pix2pixHD.wav" type="audio/wav"></audio></td>
        </tr>
        <tr>
          <td><audio controls><source src="P1/10_original.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="P1/10_initial_synthesis.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="P1/10_pix2pixHD.wav" type="audio/wav"></audio></td>
        </tr>
      </tbody>
    </table>
  </div>
  <!-- 아래에 복제 구조 (P2) -->
  <div class="table-container">
    <table>
      <caption>P2</caption>
      <thead>
        <tr>
          <th>Original</th>
          <th>Initial Synthesis</th>
          <th>Enhanced</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><audio controls><source src="P2/1_original.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="P2/1_initial_synthesis.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="P2/1_pix2pixHD.wav" type="audio/wav"></audio></td>
        </tr>
        <tr>
          <td><audio controls><source src="P2/2_original.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="P2/2_initial_synthesis.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="P2/2_pix2pixHD.wav" type="audio/wav"></audio></td>
        </tr>
        <tr>
          <td><audio controls><source src="P2/3_original.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="P2/3_initial_synthesis.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="P2/3_pix2pixHD.wav" type="audio/wav"></audio></td>
        </tr>
        <tr>
          <td><audio controls><source src="P2/4_original.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="P2/4_initial_synthesis.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="P2/4_pix2pixHD.wav" type="audio/wav"></audio></td>
        </tr>
        <tr>
          <td><audio controls><source src="P2/5_original.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="P2/5_initial_synthesis.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="P2/5_pix2pixHD.wav" type="audio/wav"></audio></td>
        </tr>
      </tbody>
    </table>
    <table>
      <caption>P2</caption>
      <thead>
        <tr>
          <th>Original</th>
          <th>Initial Synthesis</th>
          <th>Enhanced</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><audio controls><source src="P2/6_original.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="P2/6_initial_synthesis.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="P2/6_pix2pixHD.wav" type="audio/wav"></audio></td>
        </tr>
        <tr>
          <td><audio controls><source src="P2/7_original.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="P2/7_initial_synthesis.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="P2/7_pix2pixHD.wav" type="audio/wav"></audio></td>
        </tr>
        <tr>
          <td><audio controls><source src="P2/8_original.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="P2/8_initial_synthesis.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="P2/8_pix2pixHD.wav" type="audio/wav"></audio></td>
        </tr>
        <tr>
          <td><audio controls><source src="P2/9_original.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="P2/9_initial_synthesis.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="P2/9_pix2pixHD.wav" type="audio/wav"></audio></td>
        </tr>
        <tr>
          <td><audio controls><source src="P2/10_original.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="P2/10_initial_synthesis.wav" type="audio/wav"></audio></td>
          <td><audio controls><source src="P2/10_pix2pixHD.wav" type="audio/wav"></audio></td>
        </tr>
      </tbody>
    </table>
  </div>
</body>
</html>
