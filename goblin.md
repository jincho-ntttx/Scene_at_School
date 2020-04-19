# ゴブリンのプログラムの作り方(How to develop a goblin program)

## 1. プログラムを作る前の準備(Preparation before develop the program)

- Scratch 3.0を起動し、スプライト1を削除してください。(スプライト1を選択→×をクリック)

    Start Scratch 3.0 and delete sprite 1.(Select sprite 1　→　Click ×)

![Common](figure/common/startup_screen.png)

- ![Common](figure/common/sprite+button.png)ボタンをクリックしてください。

    Click on the ![Common](figure/common/sprite+button.png) button.

- ゴブリン(Goblin)を選択、クリックしてください。

    Select a goblin and click on it.

![Goblin](figure/goblin/select_sprite_goblin.png)

- スプライトが設定されていることを確認してください。

    Confirm that the selected sprite is set.

![Goblin](figure/goblin/set_sprite_goblin.png)

## 2. プログラムの作り方(How to develop a program)

### 2-1. 完成イメージ(Completed image)

![Golbin](figure/goblin/goblin_program_completed.png)

### 2-2. 作り方(How to develop)

- ![Common](figure/common/make_block_button.png)を押してください。

    Press ![Common](figure/common/make_block_button.png).

- ![Common](figure/common/building_block_button.png)を押してください。

    Press ![Common](figure/common/building_block_button.png).

- 以下の画面が表示されるので、 **『ブロック名』を『ゴブリンの会話』に変更** してください。

    When the following screen is displayed, change the "Block Name" to "Goblin Conversation" and press the OK button.

![Common](figure/common/init_screen.png)

- 『引数を追加(数値またはテキスト)』をクリックし、 **『number or text』を『ゴブリンのセリフ』に変更** 後、OKボタンを押してください。

    Click "Add argument (number or text)", change "number or text" to "Goblin's line", and then click OK.

![Goblin](figure/goblin/goblin_line.png)

- 以下の画面が表示されることを確認してください。

    Confirm that the following screen is displayed.

![Goblin](figure/goblin/goblin_talk_definition.png)

- 以下のブロックを画面中央にドラック＆ドロップします。

    Drag and drop the following blocks to the center of the screen.

![Common](figure/common/costume_button.png) ![Common](figure/common/hello.png)

![Common](figure/common/tspeech_button.png) ![Common](figure/common/speech.png)

![Common](figure/common/trans_button.png) ![Common](figure/common/trans.png)

- ![Common](figure/common/hello.png)の **『こんにちは！』に** ![Goblin](figure/goblin/goblin_line_param.png) をドラッグ＆ドロップしてください。

    Drag and drop the ![Goblin](figure/goblin/goblin_line_param.png) into "Hello" in ![Common](figure/common/hello.png).

![Goblin](figure/goblin/goblin_line_say.png)

- ![Common](figure/common/trans.png)の **『こんにちわ』に** ![Goblin](figure/goblin/goblin_line_param.png)をドラッグ＆ドロップしてください。

    Drag and drop the ![Goblin](figure/goblin/goblin_line_param.png) into "Hello" in ![Common](figure/common/trans.png).

![Goblin](figure/goblin/trans_goblin_line.png)

- ![Goblin](figure/goblin/trans_goblin_line_small.png)の▼ボタンを押し、表示される言語の一覧から **『英語』を選んでください** 。

    Press the ▼ button on ![Goblin](figure/goblin/trans_goblin_line_small.png)A and select "English" from the list of languages displayed.

![Goblin](figure/goblin/set_goblin_line_english.png)

- ![Common](figure/common/speech.png)の『hello』に![Goblin](figure/goblin/set_goblin_line_english_small.png)をドラッグ＆ドロップしてください。

    Drag and drop ![Goblin](figure/goblin/set_goblin_line_english_small.png) to "hello" in ![Common](figure/common/speech.png).

![Goblin](figure/goblin/speech_connect_trans.png)

- ブロックをくっつけてください。

    Connect the blocks.

![Goblin](figure/goblin/goblin_talk_program.png)

- ![Common](figure/common/variable_button.png)を押してください。

    Press ![Common](figure/common/variable_button.png).

- ![Common](figure/common/list_button.png)を押してください。

    Press ![Common](figure/common/list_button.png).

- **『新しいリスト名：』に『ゴブリンの会話』と入力** 後、 **『このスプライトのみ』** を選択してOKボタンを押してください。

    Enter "Goblin Conversation" in the "New List Name:" field, then select "This Sprite Only" and click OK.

![Common](figure/common/make_new_list.png)

- 空のリストが画面上に表示されることを確認してください。

    Confirm that the blank list display on the screen.

![Goblin](figure/goblin/blank_list.png)

- リストの＋ボタンを押し、 **『おはよう』と『宿題やった？』と『はーい。』を設定** してください。

Press the + button on the list and set the "Good morning" and "Did you do your homework?" and "Yes" settings.

![Goblin](figure/goblin/goblin_conversation_list.png)

- 以下のブロックを画面中央にドラック＆ドロップします。

    Drag and drop the following blocks to the center of the screen.

![Common](figure/common/costume_button.png) ![Common](figure/common/costume_display.png) ![Goblin](figure/goblin/goblin_costume.png)

![Common](figure/common/event_button.png) ![Common](figure/common/flag.png) ![Common](figure/common/message.png)

![Common](figure/common/variable_button.png) ![Goblin](figure/goblin/goblin_list_hidden.png) ![Goblin](figure/goblin/goblin_talk.png)

![Common](figure/common/make_block_button.png) ![Golbin](figure/goblin/goblin_talk_block.png)

![Common](figure/common/tspeech_button.png) ![Common](figure/common/voice.png)

- ![Golbin](figure/goblin/goblin_talk_block.png)に![Goblin](figure/goblin/goblin_talk.png)をドラック＆ドロップしてください。

    Drag and drop ![Goblin](figure/goblin/goblin_talk.png) to ![Golbin](figure/goblin/goblin_talk_block.png).

![Goblin](figure/goblin/goblin_talk1.png)

- ![Goblin](figure/goblin/goblin_costume.png)の▼ボタンを押し、表示されるコスチュームの一覧から **『goblin-b』を選んでください** 。

    Press ▼ on ![Goblin](figure/goblin/goblin_costume.png) and select "goblin-b" from the list of costumes that display.

![Goblin](figure/goblin/goblin_costumeb.png)

- ブロックをくっつけてください。

    Connect the blocks.

![Goblin](figure/goblin/goblin_program1.png)

- 以下のブロックを画面中央にドラック＆ドロップします。

    Drag and drop the following blocks to the center of the screen.

![Common](figure/common/costume_button.png) ![Goblin](figure/goblin/goblin_costume.png)

![Common](figure/common/event_button.png) ![Common](figure/common/message.png) ![Common](figure/common/message_rcv.png)

![Common](figure/common/variable_button.png) ![Goblin](figure/goblin/goblin_talk.png)

![Common](figure/common/make_block_button.png) ![Golbin](figure/goblin/goblin_talk_block.png)

- ![Golbin](figure/goblin/goblin_talk_block.png)に![Goblin](figure/goblin/goblin_talk.png)をドラック＆ドロップしてください。

    Drag and drop ![Goblin](figure/goblin/goblin_talk.png) to ![Golbin](figure/goblin/goblin_talk_block.png).

![Goblin](figure/goblin/goblin_talk1.png)

- ![Goblin](figure/goblin/goblin_talk1_small.png)の数字を **2に変更** します。(数字をダブルクリックすることで、数字を編集できる状態になります。)

    Change the number ![Goblin](figure/goblin/goblin_talk1_small.png) to 2. (Double-clicking on a number, you will be able to edit the number.)

![Goblin](figure/goblin/goblin_talk2.png)

- ![Common](figure/common/message_rcv.png)の▼ボタンを押して **『新しいメッセージ』** を選択し、以下の画面が表示されることを確認してください。

    Press ▼ on ![Common](figure/common/message_rcv.png) to select "New Message" and confirm that the following screen is displayed.

![Common](figure/common/message_new_rcv.png)

- **『新しいメッセージ名』** に **『メッセージ2』** と入力し、OKボタンを押してください。

    Enter "Message 2" in the "New Message Name" field and press the OK button.

- ![Common](figure/common/message.png)の▼ボタンを押して **『新しいメッセージ』** を選択し、以下の画面が表示されることを確認してください。

    Press ▼ on ![Common](figure/common/message.png) to select "New Message" and confirm that the following screen is displayed.

![Common](figure/common/message_new_send.png)

- **『新しいメッセージ名』** に **『メッセージ3』** と入力し、OKボタンを押してください。

    Enter "Message 3" in the "New Message Name" field and press the OK button.

- ブロックをくっつけてください。

    Connect the blocks.

![Goblin](figure/goblin/goblin_program2.png)

- 以下のブロックを画面中央にドラック＆ドロップします。

    Drag and drop the following blocks to the center of the screen.

![Common](figure/common/costume_button.png) ![Goblin](figure/goblin/goblin_costume.png) ![Common](figure/common/costume_hidden.png)

![Common](figure/common/event_button.png) ![Common](figure/common/message_rcv.png)

![Common](figure/common/control_button.png) ![Common](figure/common/wait_sec.png)

![Common](figure/common/variable_button.png) ![Goblin](figure/goblin/goblin_talk.png)

![Common](figure/common/make_block_button.png) ![Golbin](figure/goblin/goblin_talk_block.png)

- ![Golbin](figure/goblin/goblin_talk_block.png)に![Goblin](figure/goblin/goblin_talk.png)をドラック＆ドロップしてください。

    Drag and drop ![Goblin](figure/goblin/goblin_talk.png) to ![Golbin](figure/goblin/goblin_talk_block.png).

![Goblin](figure/goblin/goblin_talk1.png)

- ![Goblin](figure/goblin/goblin_talk1_small.png)の数字を **3に変更** します。(数字をダブルクリックすることで、数字を編集できる状態になります。)

    Change the number ![Goblin](figure/goblin/goblin_talk1_small.png) to 3. (Double-clicking on a number, you will be able to edit the number.)

![Goblin](figure/goblin/goblin_talk3.png)

- ![Common](figure/common/message_rcv.png)の▼ボタンを押して **『新しいメッセージ』** を選択し、以下の画面が表示されることを確認してください。

    Press ▼ on ![Common](figure/common/message_rcv.png) to select "New Message" and confirm that the following screen is displayed.

![Common](figure/common/message_new_rcv.png)

- **『新しいメッセージ名』** に **『メッセージ5』** と入力し、OKボタンを押してください。

    Enter "Message 2" in the "New Message Name" field and press the OK button.

- ![Goblin](figure/goblin/goblin_costume.png)の▼ボタンを押し、表示されるコスチュームの一覧から **『goblin-b』を選んでください** 。

    Press ▼ on ![Goblin](figure/goblin/goblin_costume.png) and select "goblin-b" from the list of costumes that display.

![Goblin](figure/goblin/goblin_costumeb.png)

- ブロックをくっつけてください。

    Connect the blocks.

![Goblin](figure/goblin/goblin_program3.png)

- 最後に、プログラムを保存してください。

    Finally, save the program.

![Common](figure/common/save.png)
