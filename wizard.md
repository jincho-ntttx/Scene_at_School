# ウィザードのプログラムの作り方(How to develop a wizard program)

## 1. プログラムを作る前の準備(Preparation before develop the program)

- ![Common](figure/common/sprite+button.png)ボタンをクリックしてください。

    Click on the ![Common](figure/common/sprite+button.png) button.

- ウィザード(Wizard)を選択、クリックしてください。

    Select a wizard and click on it.

![Wizard](figure/wizard/select_sprite_wizard.png)

- スプライトが設定されていることを確認してください。

    Confirm that the selected sprite is set.

![Wizard](figure/wizard/set_sprite_wizard.png)

- コスチュームタブをクリックし、以下の画面を表示してください。

    Click on the Costumes tab to view the following screen.

![Wizard](figure/wizard/costume_wizard_screen.png)

- wizard-aのコスチュームを選択し、![Common](figure/common/reversal_button.png)ボタンを押して、コスチュームの向きを変えてください。(wizard-bとwizard-cのコスチュームにも同じことを行ってください)

    Select the wizard-a costume and press the A button to change the orientation of the costume. (Do the same for the wizard-b and wizard-c costumes).

![Wizard](figure/wizard/costume_wizard_screen_reversal.png)

- 最後に、コードのタブをクリックしてください。

Finally, click on the Code tab.

## 1. プログラムの作り方(How to develop a program)

### 1-1. 完成イメージ(Completed image)

![Wizard](figure/wizard/wizard_program_completed.png)

### 1-2. 作り方(How to develop)

- ![Common](figure/common/make_block_button.png)を押してください。

    Press ![Common](figure/common/make_block_button.png).

- ![Common](figure/common/building_block_button.png)を押してください。

    Press ![Common](figure/common/building_block_button.png).

- 以下の画面が表示されるので、 **『ブロック名』を『先生の会話』に変更** してください。

    When the following screen is displayed, change the "Block Name" to "Teacher Conversation" and press the OK button.

![Common](figure/common/init_screen.png)

- 『引数を追加(数値またはテキスト)』をクリックし、 **『number or text』を『先生のセリフ』に変更** 後、OKボタンを押してください。

    Click "Add argument (number or text)", change "number or text" to "The teacher's line", and then click OK.

![Wizard](figure/wizard/teacher_line.png)

- 以下の画面が表示されることを確認してください。

    Confirm that the following screen is displayed.

![Wizard](figure/wizard/teacher_talk_definition.png)

- 以下のブロックを画面中央にドラック＆ドロップします。

    Drag and drop the following blocks to the center of the screen.

![Common](figure/common/costume_button.png) ![Common](figure/common/hello.png)

![Common](figure/common/tspeech_button.png) ![Common](figure/common/speech.png)

![Common](figure/common/trans_button.png) ![Common](figure/common/trans.png)

- ![Common](figure/common/hello.png)の **『こんにちは！』に** ![Wizard](figure/wizard/teacher_line_block.png) をドラッグ＆ドロップしてください。

    Drag and drop the ![Wizard](figure/wizard/teacher_line_block.png) into "Hello" in ![Common](figure/common/hello.png).

![Wizard](figure/wizard/wizard_line_say.png)

- ![Common](figure/common/trans.png)の **『こんにちわ』に** ![Wizard](figure/wizard/teacher_line_block.png)をドラッグ＆ドロップしてください。

    Drag and drop the ![Wizard](figure/wizard/teacher_line_block.png) into "Hello" in ![Common](figure/common/trans.png).

![Wizard](figure/wizard/trans_teacher_line.png)

- ![Wizard](figure/wizard/trans_teacher_line_small.png)の▼ボタンを押し、表示される言語の一覧から **『英語』を選んでください** 。

    Press the ▼ button on ![Wizard](figure/wizard/trans_teacher_line_small.png)A and select "English" from the list of languages displayed.

![Wizard](figure/wizard/trans_teacher_line_english.png)

- ![Common](figure/common/speech.png)の『hello』に![Wizard](figure/wizard/trans_teacher_line_english_small.png)をドラッグ＆ドロップしてください。

    Drag and drop ![Frank](figure/frank/set_frank_line_english_small.png) to "hello" in ![Common](figure/common/speech.png).

![Wizard](figure/wizard/speech_connect_trans.png)

- ブロックをくっつけてください。

    Connect the blocks.

![Wizard](figure/wizard/teacher_talk_program.png)

- ![Common](figure/common/variable_button.png)を押してください。

    Press ![Common](figure/common/variable_button.png).

- ![Common](figure/common/list_button.png)を押してください。

    Press ![Common](figure/common/list_button.png).

- **『新しいリスト名：』に『先生の会話』と入力** 後、 **『このスプライトのみ』** を選択してOKボタンを押してください。

    Enter "Teacher Conversation" in the "New List Name:" field, then select "This Sprite Only" and click OK.

![Common](figure/common/make_new_list.png)

- 空のリストが画面上に表示されることを確認してください。

    Confirm that the blank list display on the screen.

![Wizard](figure/wizard/blank_list.png)

- リストの＋ボタンを押し、 **『授業を始めるぞ！』を設定** してください。

Press the + button on the list and set the "Let's the start the class!" settings.

![Wizard](figure/wizard/teacher_conversation_list.png)

- 以下のブロックを画面中央にドラック＆ドロップします。

    Drag and drop the following blocks to the center of the screen.

![Common](figure/common/costume_button.png) ![Common](figure/common/costume_hidden.png)

![Common](figure/common/event_button.png) ![Common](figure/common/flag.png)

![Common](figure/common/variable_button.png) ![Frank](figure/frank/frank_list_hidden.png)

![Common](figure/common/tspeech_button.png) ![Common](figure/common/voice.png)

- ![Common](figure/common/voice.png)を **『アルト』から『テノール』に変更** する。

    Change ![Common](figure/common/voice.png) from "Alto" to "Tenor".

![Wizard](figure/wizard/tenor_voise.png)

- ブロックをくっつけてください。

    Connect the blocks.

![Wizard](figure/wizard/teacher_program1.png)

- 以下のブロックを画面中央にドラック＆ドロップします。

    Drag and drop the following blocks to the center of the screen.

![Common](figure/common/costume_button.png) ![Wizard](figure/wizard/teacher_costume_a.png) ![Common](figure/common/costume_display.png) ![Common](figure/common/costume_hidden.png)

![Common](figure/common/event_button.png) ![Common](figure/common/message.png) ![Common](figure/common/message_rcv.png)

![Common](figure/common/variable_button.png) ![Wizard](figure/wizard/teacher_talk.png)

![Common](figure/common/make_block_button.png) ![Wizard](figure/wizard/teacher_talk_block.png)

- ![Wizard](figure/wizard/teacher_costume_a.png)の▼ボタンを押し、表示されるコスチュームの一覧から **『wizard-c』を選んでください** 。

    Press ▼ on ![Wizard](figure/wizard/teacher_costume_a.png) and select "frank-c" from the list of costumes that display.

![Wizard](figure/wizard/teacher_costume_c.png)

- ![Common](figure/common/message_rcv.png)の▼ボタンを押して **『メッセージ4』** を選択し、以下の画面が表示されることを確認してください。

    Press ▼ on ![Common](figure/common/message_rcv.png) to select "Message 4" and confirm that the following screen is displayed.

![Wizard](figure/wizard/message4.png)

- ![Common](figure/common/message.png)の▼ボタンを押して **『メッセージ5』** を選択し、以下の画面が表示されることを確認してください。

    Press ▼ on ![Common](figure/common/message.png) to select "Message 5" and confirm that the following screen is displayed.

![Wizard](figure/wizard/message5.png)

- ![Wizard](figure/wizard/teacher_talk_block.png)に![Wizard](figure/wizard/teacher_talk.png)をドラック＆ドロップしてください。

    Drag and drop ![Wizard](figure/wizard/teacher_talk.png) to ![Wizard](figure/wizard/teacher_talk_block.png).

![Wizard](figure/wizard/teacher_conversation1.png)

- ブロックをくっつけてください。

    Connect the blocks.

![Wizard](figure/wizard/teacher_program2.png)
