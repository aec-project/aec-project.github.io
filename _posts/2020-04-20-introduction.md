---
layout: post
title: Title of the paper
---

## Abstract

-- Abstract part --

-----

## Audio Samples in Doubletalk Scenario

### Evaluation samples
Synthetic test set DoubleTalk

<table>
  <thead>
    <tr>
      <th>Sample</th>
      <th>Microphone</th>
      <th>Far-end speech</th>
      <th>Ground-Truth</th>
      <th>DTLN</th>
      <th>FTLSTM</th>
      <th>Proposed</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Sample 1</td>
      <td><audio controls  src="samples/mic_syn_babble_ser_-6db_00085.wav"> </audio></td>
      <td><audio controls  src="samples/farend_syn_00085.wav"> </audio></td>
      <td><audio controls  src="samples/nearend_babble_ser_-6db_00085.wav"> </audio></td>
      <td><audio controls  src="samples/dtln_syn_babble_00085_babble_10dB.wav"> </audio></td>
      <td><audio controls  src="samples/ftlstm_syn_babble_00085_babble_10dB.wav"> </audio></td>
      <td><audio controls  src="samples/ours_syn_babble_00085_babble_10dB.wav"> </audio></td>
    </tr>
      <tr>
      <td>Sample 2</td>
      <td><audio controls  src="samples/mic_syn_real_ser_-6db_00127.wav"> </audio></td>
      <td><audio controls  src="samples/farend_syn_00127.wav"> </audio></td>
      <td><audio controls  src="samples/nearend_real_ser_-6db_00127.wav"> </audio></td>
      <td><audio controls  src="samples/dtln_syn_real_00127_None_20dB.wav"> </audio></td>
      <td><audio controls  src="samples/ftlstm_syn_real_00127_None_20dB.wav"> </audio></td>
      <td><audio controls  src="samples/ours_syn_real_00127_None_20dB.wav"> </audio></td>
      </tr>
    <tr>
      <td>Sample 3</td>
      <td><audio controls  src="samples/mic_syn_real_ser_-6db_00321.wav"> </audio></td>
      <td><audio controls  src="samples/farend_real_00321.wav"> </audio></td>
      <td><audio controls  src="samples/nearend_real_ser_-6db_00321.wav"> </audio></td>
      <td><audio controls  src="samples/dtln_syn_real_00321_None_10dB.wav"> </audio></td>
      <td><audio controls  src="samples/ftlstm_syn_real_00321_None_10dB.wav"> </audio></td>
      <td><audio controls  src="samples/ours_syn_real_00321_None_10dB.wav"> </audio></td>
      </tr>
    <tr>
      <td>Sample 4</td>
      <td><audio controls  src="samples/mic_syn_white_ser_-6db_00171.wav"> </audio></td>
      <td><audio controls  src="samples/farend_syn_00171.wav"> </audio></td>
      <td><audio controls  src="samples/nearend_white_ser_-6db_00171.wav"> </audio></td>
      <td><audio controls  src="samples/dtln_syn_white_00171_white_20dB.wav"> </audio></td>
      <td><audio controls  src="samples/ftlstm_syn_white_00171_white_20dB.wav"> </audio></td>
      <td><audio controls  src="samples/ours_syn_white_00171_white_20dB.wav"> </audio></td>
    </tr>
    
  </tbody>
</table>

### Blind test set from AEC Challenge
DoubleTalk

<table>
  <thead>
    <tr>
      <th> </th>
      <th>Microphone</th>
      <th>Far-end speech</th>
      <th>DTLN</th>
      <th>NKF-AEC</th>
      <th>Proposed</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Sample 1</td>
      <td><audio controls  src="samples/blind_input_hvY1v0viv0yMdAXKa2y1aw_doubletalk_with_movement_mic.wav"> </audio></td>
      <td><audio controls  src="samples/blind_input_hvY1v0viv0yMdAXKa2y1aw_doubletalk_with_movement_farend.wav"> </audio></td>
      <td><audio controls  src="samples/blind_dtln_hvY1v0viv0yMdAXKa2y1aw_doubletalk_with_movement_mic.wav"> </audio></td>
      <td><audio controls  src="samples/blind_nkfaec_hvY1v0viv0yMdAXKa2y1aw_doubletalk_with_movement_mic.wav"> </audio></td>
      <td><audio controls  src="samples/blind_ours_hvY1v0viv0yMdAXKa2y1aw_doubletalk_with_movement_mic.wav"> </audio></td>
    </tr>
      <tr>
      <td>Sample 2</td>
      <td><audio controls  src="samples/blind_input_Lsa5WpwTpUeb7C9dc9RXuQ_doubletalk_mic.wav"> </audio></td>
      <td><audio controls  src="samples/blind_input_Lsa5WpwTpUeb7C9dc9RXuQ_doubletalk_farend.wav"> </audio></td>
      <td><audio controls  src="samples/blind_dtln_Lsa5WpwTpUeb7C9dc9RXuQ_doubletalk_with_movement_mic.wav"> </audio></td>
      <td><audio controls  src="samples/blind_nkfaec_Lsa5WpwTpUeb7C9dc9RXuQ_doubletalk_with_movement_mic.wav"> </audio></td>
      <td><audio controls  src="samples/blind_ours_Lsa5WpwTpUeb7C9dc9RXuQ_doubletalk_with_movement_mic.wav"> </audio></td>
      </tr>
    <tr>
      <td>Sample 3</td>
      <td><audio controls  src="samples/blind_input_nlSSRl4k50Gq2mIRYlMBCg_doubletalk_with_movement_mic.wav"> </audio></td>
      <td><audio controls  src="samples/blind_input_nlSSRl4k50Gq2mIRYlMBCg_doubletalk_with_movement_farend.wav"> </audio></td>
      <td><audio controls  src="samples/blind_dtln_nlSSRl4k50Gq2mIRYlMBCg_doubletalk_with_movement_mic.wav"> </audio></td>
      <td><audio controls  src="samples/blind_nkfaec_nlSSRl4k50Gq2mIRYlMBCg_doubletalk_with_movement_mic.wav"> </audio></td>
      <td><audio controls  src="samples/blind_ours_nlSSRl4k50Gq2mIRYlMBCg_doubletalk_with_movement_mic.wav"> </audio></td>
      </tr>
    <tr>
      <td>Sample 4</td>
      <td><audio controls  src="samples/blind_input_TGZ5Wq0SCUCOXPsfee3uMQ_doubletalk_with_movement_mic.wav"> </audio></td>
      <td><audio controls  src="samples/blind_input_TGZ5Wq0SCUCOXPsfee3uMQ_doubletalk_with_movement_farend.wav"> </audio></td>
      <td><audio controls  src="samples/blind_dtln_TGZ5Wq0SCUCOXPsfee3uMQ_doubletalk_with_movement_mic.wav"> </audio></td>
      <td><audio controls  src="samples/blind_nkfaec_TGZ5Wq0SCUCOXPsfee3uMQ_doubletalk_with_movement_mic.wav"> </audio></td>
      <td><audio controls  src="samples/blind_ours_TGZ5Wq0SCUCOXPsfee3uMQ_doubletalk_with_movement_mic.wav"> </audio></td>
    </tr>
    
  </tbody>
</table>


Far-end SingleTalk

<table>
  <thead>
    <tr>
      <th> </th>
      <th>Microphone</th>
      <th>Far-end speech</th>
      <th>DTLN</th>
      <th>NKF-AEC</th>
      <th>Proposed</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Sample 1</td>
      <td><audio controls  src="samples/blind_input_JtodX3Ug6Eu5TYu0HN5IOw_farend_singletalk_mic.wav"> </audio></td>
      <td><audio controls  src="samples/blind_input_JtodX3Ug6Eu5TYu0HN5IOw_farend_singletalk_farend.wav"> </audio></td>
      <td><audio controls  src="samples/blind_dtln_JtodX3Ug6Eu5TYu0HN5IOw_farend_singletalk_mic.wav"> </audio></td>
      <td><audio controls  src="samples/blind_nkfaec_JtodX3Ug6Eu5TYu0HN5IOw_farend_singletalk_mic.wav"> </audio></td>
      <td><audio controls  src="samples/blind_ours_JtodX3Ug6Eu5TYu0HN5IOw_farend_singletalk_mic.wav"> </audio></td>
    </tr>
      <tr>
      <td>Sample 2</td>
      <td><audio controls  src="samples/blind_input_KOy0eftktkuJf180xtXudg_farend_singletalk_mic.wav"> </audio></td>
      <td><audio controls  src="samples/blind_input_KOy0eftktkuJf180xtXudg_farend_singletalk_farend.wav"> </audio></td>
      <td><audio controls  src="samples/blind_dtln_KOy0eftktkuJf180xtXudg_farend_singletalk_mic.wav"> </audio></td>
      <td><audio controls  src="samples/blind_nkfaec_KOy0eftktkuJf180xtXudg_farend_singletalk_mic.wav"> </audio></td>
      <td><audio controls  src="samples/blind_ours_KOy0eftktkuJf180xtXudg_farend_singletalk_mic.wav"> </audio></td>
      </tr>
    <tr>
      <td>Sample 3</td>
      <td><audio controls  src="samples/blind_input_mXuYaMbcZka0TpdHDdTlWA_farend_singletalk_mic.wav"> </audio></td>
      <td><audio controls  src="samples/blind_input_mXuYaMbcZka0TpdHDdTlWA_farend_singletalk_farend.wav"> </audio></td>
      <td><audio controls  src="samples/blind_dtln_mXuYaMbcZka0TpdHDdTlWA_farend_singletalk_mic.wav"> </audio></td>
      <td><audio controls  src="samples/blind_nkfaec_mXuYaMbcZka0TpdHDdTlWA_farend_singletalk_mic.wav"> </audio></td>
      <td><audio controls  src="samples/blind_ours_mXuYaMbcZka0TpdHDdTlWA_farend_singletalk_mic.wav"> </audio></td>
      </tr>
    <tr>
      <td>Sample 4</td>
      <td><audio controls  src="samples/blind_input_Uc4dmejgWUCTvn0XZbMTBw_farend_singletalk_mic.wav"> </audio></td>
      <td><audio controls  src="samples/blind_input_Uc4dmejgWUCTvn0XZbMTBw_farend_singletalk_farend.wav"> </audio></td>
      <td><audio controls  src="samples/blind_dtln_Uc4dmejgWUCTvn0XZbMTBw_farend_singletalk_mic.wav"> </audio></td>
      <td><audio controls  src="samples/blind_nkfaec_Uc4dmejgWUCTvn0XZbMTBw_farend_singletalk_mic.wav"> </audio></td>
      <td><audio controls  src="samples/blind_ours_Uc4dmejgWUCTvn0XZbMTBw_farend_singletalk_mic.wav"> </audio></td>
    </tr>
    
  </tbody>
</table>