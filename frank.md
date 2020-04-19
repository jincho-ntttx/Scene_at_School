# フランクのプログラムの作り方(How to develop a frank program)

## 1. プログラムを作る前の準備(Preparation before develop the program)

- ![Common](figure/common/sprite+button.png)ボタンをクリックしてください。

    Click on the ![Common](figure/common/sprite+button.png) button.

- フランク(Frank)を選択、クリックしてください。

    Select a frank and click on it.

![Frank](figure/frank/select_sprite_frank.png)

- スプライトが設定されていることを確認してください。

    Confirm that the selected sprite is set.

![Frank](figure/frank/set_sprite_frank.png)

## 2. プログラムの作り方(How to develop a program)

### 2-1. 完成イメージ(Completed image)

![Frank](figure/frank/frank_program_completed.png)

### 2-2. 作り方(How to develop)

- ![Common](figure/common/make_block_button.png)を押してください。

    Press ![Common](figure/common/make_block_button.png).

- ![Common](figure/common/building_block_button.png)を押してください。

    Press ![Common](figure/common/building_block_button.png).

- 以下の画面が表示されるので、 **『ブロック名』を『フランクの会話』に変更** してください。

    When the following screen is displayed, change the "Block Name" to "Frank Conversation" and press the OK button.

![Common](figure/common/init_screen.png)

- 『引数を追加(数値またはテキスト)』をクリックし、 **『number or text』を『フランクのセリフ』に変更** 後、OKボタンを押してください。

    Click "Add argument (number or text)", change "number or text" to "Frank's line", and then click OK.

![Frank](figure/frank/frank_line.png)

- 以下の画面が表示されることを確認してください。

    Confirm that the following screen is displayed.

![Frank](figure/frank/frank_talk_definition.png)

- 以下のブロックを画面中央にドラック＆ドロップします。

    Drag and drop the following blocks to the center of the screen.

![Common](figure/common/costume_button.png) ![Common](figure/common/hello.png)

![Common](figure/common/tspeech_button.png) ![Common](figure/common/speech.png)

![Common](figure/common/trans_button.png) ![Common](figure/common/trans.png)

- ![Common](figure/common/hello.png)の **『こんにちは！』に** ![Frank](figure/frank/frank_line_param.png) をドラッグ＆ドロップしてください。

    Drag and drop the ![Frank](figure/frank/frank_line_param.png) into "Hello" in ![Common](figure/common/hello.png).

![Frank](figure/frank/frank_line_say.png)

- ![Common](figure/common/trans.png)の **『こんにちわ』に** ![Frank](figure/frank/frank_line_param.png)をドラッグ＆ドロップしてください。

    Drag and drop the ![Frank](figure/frank/frank_line_param.png) into "Hello" in ![Common](figure/common/trans.png).

![Frank](figure/frank/trans_frank_line.png)

- ![Frank](figure/frank/trans_frank_line_small.png)の▼ボタンを押し、表示される言語の一覧から **『英語』を選んでください** 。

    Press the ▼ button on ![Frank](figure/frank/trans_frank_line_small.png)A and select "English" from the list of languages displayed.

![Frank](figure/frank/set_frank_line_english.png)

- ![Common](figure/common/speech.png)の『hello』に![Frank](figure/frank/set_frank_line_english_small.png)をドラッグ＆ドロップしてください。

    Drag and drop ![Frank](figure/frank/set_frank_line_english_small.png) to "hello" in ![Common](figure/common/speech.png).

![Frank](figure/frank/speech_connect_trans.png)

- ブロックをくっつけてください。

    Connect the blocks.

![Frank](figure/frank/frank_talk_program.png)

- ![Common](figure/common/variable_button.png)を押してください。

    Press ![Common](figure/common/variable_button.png).

- ![Common](figure/common/list_button.png)を押してください。

    Press ![Common](figure/common/list_button.png).

- **『新しいリスト名：』に『フランクの会話』と入力** 後、 **『このスプライトのみ』** を選択してOKボタンを押してください。

    Enter "Frank Conversation" in the "New List Name:" field, then select "This Sprite Only" and click OK.

![Common](figure/common/make_new_list.png)

- 空のリストが画面上に表示されることを確認してください。

    Confirm that the blank list display on the screen.

![Frank](figure/frank/blank_list.png)

- リストの＋ボタンを押し、 **『おはよう』と『忘れた…』と『どうしよう…』を設定** してください。

Press the + button on the list and set the "Good morning" and "I forget…" and "What should I do?" settings.

![Frank](figure/frank/frank_conversation_list.png)

- 以下のブロックを画面中央にドラック＆ドロップします。

    Drag and drop the following blocks to the center of the screen.

![Common](figure/common/costume_button.png) ![Common](figure/common/costume_display.png)

![Common](figure/common/event_button.png) ![Common](figure/common/flag.png)

![Common](figure/common/variable_button.png) ![Frank](figure/frank/frank_list_hidden.png)

![Common](figure/common/tspeech_button.png) ![Common](figure/common/voice.png)

- ![Common](figure/common/voice.png)を **『アルト』から『巨人』に変更** する。

    Change ![Common](figure/common/voice.png) from "Alto" to "Giant".

![Frank](figure/frank/giant_voise.png)

- ブロックをくっつけてください。

    Connect the blocks.

![Frank](figure/frank/frank_program1.png)

- 以下のブロックを画面中央にドラック＆ドロップします。

    Drag and drop the following blocks to the center of the screen.

![Common](figure/common/costume_button.png) ![Frank](figure/frank/frank_costume_a.png)

![Common](figure/common/event_button.png) ![Common](figure/common/message.png) ![Common](figure/common/message_rcv.png)

![Common](figure/common/variable_button.png) ![Frank](figure/frank/frank_talk.png)

![Common](figure/common/make_block_button.png) ![Frank](figure/frank/frank_talk_block.png)

- ![Frank](figure/frank/frank_costume_a.png)の▼ボタンを押し、表示されるコスチュームの一覧から **『frank-c』を選んでください** 。

    Press ▼ on ![Frank](figure/frank/frank_costume_a.png) and select "frank-c" from the list of costumes that display.

![Frank](figure/frank/frank_costume_c.png)

- ![Common](figure/common/message.png)の▼ボタンを押して **『メッセージ2』** を選択し、以下の画面が表示されることを確認してください。

    Press ▼ on ![Common](figure/common/message.png) to select "Message 2" and confirm that the following screen is displayed.

![Frank](figure/frank/message2.png)

- ![Frank](figure/frank/frank_talk_block.png)に![Frank](figure/frank/frank_talk.png)をドラック＆ドロップしてください。

    Drag and drop ![Frank](figure/frank/frank_talk.png) to ![Frank](figure/frank/frank_talk_block.png).

![Frank](figure/frank/frank_conversation1.png)

- ブロックをくっつけてください。

    Connect the blocks.

![Frank](figure/frank/frank_program2.png)

- 以下のブロックを画面中央にドラック＆ドロップします。

    Drag and drop the following blocks to the center of the screen.

![Common](figure/common/costume_button.png) ![Frank](figure/frank/frank_costume_a.png)

![Common](figure/common/event_button.png) ![Common](figure/common/message.png) ![Common](figure/common/message_rcv.png)

![Common](figure/common/variable_button.png) ![Frank](figure/frank/frank_talk.png)

![Common](figure/common/make_block_button.png) ![Frank](figure/frank/frank_talk_block.png)

- ![Common](figure/common/message_rcv.png)の▼ボタンを押して **『メッセージ3』** を選択し、以下の画面が表示されることを確認してください。

    Press ▼ on ![Common](figure/common/message_rcv.png) to select "Message 3" and confirm that the following screen is displayed.

![Frank](figure/frank/message_rcv3.png)

- ![Frank](figure/frank/frank_costume_a.png)の▼ボタンを押し、表示されるコスチュームの一覧から **『frank-d』を選んでください** 。

    Press ▼ on ![Frank](figure/frank/frank_costume_a.png) and select "frank-d" from the list of costumes that display.

![Frank](figure/frank/frank_costume_d.png)

- ![Frank](figure/frank/frank_talk_block.png)に![Frank](figure/frank/frank_talk.png)をドラック＆ドロップしてください。

    Drag and drop ![Frank](figure/frank/frank_talk.png) to ![Frank](figure/frank/frank_talk_block.png).

![Frank](figure/frank/frank_conversation1.png)

- ![Frank](figure/frank/frank_conversation1_small.png)の数字を **2に変更** します。(数字をダブルクリックすることで、数字を編集できる状態になります。)

    Change the number ![Frank](figure/frank/frank_conversation1_small.png) to 2. (Double-clicking on a number, you will be able to edit the number.)

![Frank](figure/frank/frank_conversation2.png)

- ![Common](figure/common/message.png)の▼ボタンを押して **『新しいメッセージ』** を選択し、以下の画面が表示されることを確認してください。

    Press ▼ on ![Common](figure/common/message.png) to select "New Message" and confirm that the following screen is displayed.

![Common](figure/common/message_new_send.png)

- **『新しいメッセージ名』** に **『メッセージ4』** と入力し、OKボタンを押してください。

    Enter "Message 4" in the "New Message Name" field and press the OK button.

![Frank](figure/frank/message4.png)

- ブロックをくっつけてください。

    Connect the blocks.

![Frank](figure/frank/frank_program3.png)

- 以下のブロックを画面中央にドラック＆ドロップします。

    Drag and drop the following blocks to the center of the screen.

![Common](figure/common/costume_button.png) ![Frank](figure/frank/frank_costume_a.png) ![Common](figure/common/costume_hidden.png)

![Common](figure/common/event_button.png) ![Common](figure/common/message_rcv.png)

![Common](figure/common/control_button.png) ![Common](figure/common/wait_sec.png)

![Common](figure/common/variable_button.png) ![Frank](figure/frank/frank_talk.png)

![Common](figure/common/make_block_button.png) ![Frank](figure/frank/frank_talk_block.png)

- ![Common](figure/common/message_rcv.png)の▼ボタンを押して **『メッセージ5』** を選択し、以下の画面が表示されることを確認してください。

    Press ▼ on ![Common](figure/common/message_rcv.png) to select "Message 5" and confirm that the following screen is displayed.

![Frank](figure/frank/message_rcv5.png)

- ![Frank](figure/frank/frank_costume_a.png)の▼ボタンを押し、表示されるコスチュームの一覧から **『frank-b』を選んでください** 。

    Press ▼ on ![Frank](figure/frank/frank_costume_a.png) and select "frank-b" from the list of costumes that display.

![Frank](figure/frank/frank_costume_b.png)

- ![Frank](figure/frank/frank_talk_block.png)に![Frank](figure/frank/frank_talk.png)をドラック＆ドロップしてください。

    Drag and drop ![Frank](figure/frank/frank_talk.png) to ![Frank](figure/frank/frank_talk_block.png).

![Frank](figure/frank/frank_conversation1.png)

- ![Frank](figure/frank/frank_conversation1_small.png)の数字を **3に変更** します。(数字をダブルクリックすることで、数字を編集できる状態になります。)

    Change the number ![Frank](figure/frank/frank_conversation1_small.png) to 3. (Double-clicking on a number, you will be able to edit the number.)

![Frank](figure/frank/frank_conversation3.png)

- ブロックをくっつけてください。

    Connect the blocks.

![Frank](figure/frank/frank_program4.png)

- 最後に、プログラムを保存してください。

    Finally, save the program.

![Common](figure/common/save.png)
