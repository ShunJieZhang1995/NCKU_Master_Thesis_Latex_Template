## National Cheng Kung University (NCKU) Thesis Template in LaTex ##
### 國立成功大學碩士用畢業論文LaTex模版 ###

這是國立成功大學碩博士用畢業論文的LaTex模版. 這模版是以 [105.12.15 105學年度第2次教務會議修正過](http://cid.acad.ncku.edu.tw/ezfiles/56/1056/img/730/degree4-1.pdf) 的畢業論文要求，並參考[wengan-li](https://github.com/wengan-li/ncku-thesis-template-latex)以及成大機械系[吳馬丁教授](http://www.me.ncku.edu.tw/tw/content/%E5%90%B3%E9%A6%AC%E4%B8%81)實驗室所使用模板來設計。筆者於2021年一月碩士論文審查通過畢業，此模板應該沒有問題。使用時請留意學校的最新所訂的要求能否使用這模版。

---
### Main feature 主要功能
  1. 能同時讓你編寫中英文內容 (建基於XeLaTex)
  2. 提供相較於[wengan-li](https://github.com/wengan-li/ncku-thesis-template-latex)更加簡潔易懂的模板檔案結構
  3. 主要資料能自動產生
  4. 內含基本的LaTex使用教學及筆者的寫作經驗
---
### Environment 環境
LaTex環境使用[MiKTeX](https://miktex.org/)。推薦編輯器為[VScode](https://code.visualstudio.com/)，並安裝延伸模組[LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)，延伸模組相關設定請參考[settings_for_vscode.json](https://github.com/ShunJieZhang1995/NCKU_Master_Thesis_Latex_Template/blob/master/settings_for_vscode.json)。

設定完成後在VScode中按下Ctrl+B即可編譯，編譯完後按下Ctrl+V即可預覽結果。
預設編譯路徑為"xelatex-> makeindex-> bibtex-> xelatex\*2"。若沒有使用List of Symbols章節，則可以省略makeindex，將json檔中"xelatex-> bibtex-> xelatex\*2"改到首位即可修改預設編譯方法。

---
而本模版所使用到的國立成功大學浮水印則由國立成功大學擁有**所有**相關的權利。故如使用這浮水印到論文以外的應用，請跟"成大圖書館 系統管理組-數位論文小組"聯絡。