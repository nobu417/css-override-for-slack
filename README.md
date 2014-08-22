Slack の上書き用CSS。
サイドバーを小さくして、小さいウィンドウでも開きやすく。常駐向けに。
ユーザーの発言は吹き出しにした。

```css
body {
    min-width: 100px !important;
	font-family: 'Helvetica Neue' !imporatant;
}

#monkey_scroll_wrapper_for_msgs_scroller_div {
	min-width: auto !important;
    font-size: 0.7em !important;
}

#col_channels_bg {
    width: 160px;
    font-size: 0.8em !important;
}

#team_menu {
    width: 160px !important;
}

#user_menu {
    width: 160px !important;
}

#col_channels {
    width: 160px !important;
}

#search_container {
    display: none;
}

#messages_container {
    margin-left: 160px !important;
}

.message_sender.member {
	font-size: 10pt;
}

.message_content {
	border-radius: 9px;
	margin-left: 4px;
	background-color: #f0f0f0;
	padding: 6px 10px;
	font-size: 9pt;
	line-height: 14pt;
}

.message_content:before {
	content: '';
	position: absolute;
	margin-top: -4px;
	margin-left: -18px;
	border-top: 12px solid #f0f0f0;
	border-right: 5px solid transparent;
	border-left: 5px solid transparent;
	-webkit-transform: rotate(116deg);
}

#footer {
    left: 160px !important;
}
```
