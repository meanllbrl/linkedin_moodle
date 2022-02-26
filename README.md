<html><head><meta http-equiv="Content-Type" content="text/html; charset=utf-8"><title>Untitled</title><style>
/* cspell:disable-file */
/* webkit printing magic: print all background colors */
html {
	-webkit-print-color-adjust: exact;
}
* {
	box-sizing: border-box;
	-webkit-print-color-adjust: exact;
}

html,
body {
	margin: 0;
	padding: 0;
}
@media only screen {
	body {
		margin: 2em auto;
		max-width: 900px;
		color: rgb(55, 53, 47);
	}
}

body {
	line-height: 1.5;
	white-space: pre-wrap;
}

a,
a.visited {
	color: inherit;
	text-decoration: underline;
}

.pdf-relative-link-path {
	font-size: 80%;
	color: #444;
}

h1,
h2,
h3 {
	letter-spacing: -0.01em;
	line-height: 1.2;
	font-weight: 600;
	margin-bottom: 0;
}

.page-title {
	font-size: 2.5rem;
	font-weight: 700;
	margin-top: 0;
	margin-bottom: 0.75em;
}

h1 {
	font-size: 1.875rem;
	margin-top: 1.875rem;
}

h2 {
	font-size: 1.5rem;
	margin-top: 1.5rem;
}

h3 {
	font-size: 1.25rem;
	margin-top: 1.25rem;
}

.source {
	border: 1px solid #ddd;
	border-radius: 3px;
	padding: 1.5em;
	word-break: break-all;
}

.callout {
	border-radius: 3px;
	padding: 1rem;
}

figure {
	margin: 1.25em 0;
	page-break-inside: avoid;
}

figcaption {
	opacity: 0.5;
	font-size: 85%;
	margin-top: 0.5em;
}

mark {
	background-color: transparent;
}

.indented {
	padding-left: 1.5em;
}

hr {
	background: transparent;
	display: block;
	width: 100%;
	height: 1px;
	visibility: visible;
	border: none;
	border-bottom: 1px solid rgba(55, 53, 47, 0.09);
}

img {
	max-width: 100%;
}

@media only print {
	img {
		max-height: 100vh;
		object-fit: contain;
	}
}

@page {
	margin: 1in;
}

.collection-content {
	font-size: 0.875rem;
}

.column-list {
	display: flex;
	justify-content: space-between;
}

.column {
	padding: 0 1em;
}

.column:first-child {
	padding-left: 0;
}

.column:last-child {
	padding-right: 0;
}

.table_of_contents-item {
	display: block;
	font-size: 0.875rem;
	line-height: 1.3;
	padding: 0.125rem;
}

.table_of_contents-indent-1 {
	margin-left: 1.5rem;
}

.table_of_contents-indent-2 {
	margin-left: 3rem;
}

.table_of_contents-indent-3 {
	margin-left: 4.5rem;
}

.table_of_contents-link {
	text-decoration: none;
	opacity: 0.7;
	border-bottom: 1px solid rgba(55, 53, 47, 0.18);
}

table,
th,
td {
	border: 1px solid rgba(55, 53, 47, 0.09);
	border-collapse: collapse;
}

table {
	border-left: none;
	border-right: none;
}

th,
td {
	font-weight: normal;
	padding: 0.25em 0.5em;
	line-height: 1.5;
	min-height: 1.5em;
	text-align: left;
}

th {
	color: rgba(55, 53, 47, 0.6);
}

ol,
ul {
	margin: 0;
	margin-block-start: 0.6em;
	margin-block-end: 0.6em;
}

li > ol:first-child,
li > ul:first-child {
	margin-block-start: 0.6em;
}

ul > li {
	list-style: disc;
}

ul.to-do-list {
	text-indent: -1.7em;
}

ul.to-do-list > li {
	list-style: none;
}

.to-do-children-checked {
	text-decoration: line-through;
	opacity: 0.375;
}

ul.toggle > li {
	list-style: none;
}

ul {
	padding-inline-start: 1.7em;
}

ul > li {
	padding-left: 0.1em;
}

ol {
	padding-inline-start: 1.6em;
}

ol > li {
	padding-left: 0.2em;
}

.mono ol {
	padding-inline-start: 2em;
}

.mono ol > li {
	text-indent: -0.4em;
}

.toggle {
	padding-inline-start: 0em;
	list-style-type: none;
}

/* Indent toggle children */
.toggle > li > details {
	padding-left: 1.7em;
}

.toggle > li > details > summary {
	margin-left: -1.1em;
}

.selected-value {
	display: inline-block;
	padding: 0 0.5em;
	background: rgba(206, 205, 202, 0.5);
	border-radius: 3px;
	margin-right: 0.5em;
	margin-top: 0.3em;
	margin-bottom: 0.3em;
	white-space: nowrap;
}

.collection-title {
	display: inline-block;
	margin-right: 1em;
}

.simple-table {
	margin-top: 1em;
	font-size: 0.875rem;
}

.simple-table-header {
	background: rgb(247, 246, 243);
	color: black;
	font-weight: 500;
}

time {
	opacity: 0.5;
}

.icon {
	display: inline-block;
	max-width: 1.2em;
	max-height: 1.2em;
	text-decoration: none;
	vertical-align: text-bottom;
	margin-right: 0.5em;
}

img.icon {
	border-radius: 3px;
}

.user-icon {
	width: 1.5em;
	height: 1.5em;
	border-radius: 100%;
	margin-right: 0.5rem;
}

.user-icon-inner {
	font-size: 0.8em;
}

.text-icon {
	border: 1px solid #000;
	text-align: center;
}

.page-cover-image {
	display: block;
	object-fit: cover;
	width: 100%;
	max-height: 30vh;
}

.page-header-icon {
	font-size: 3rem;
	margin-bottom: 1rem;
}

.page-header-icon-with-cover {
	margin-top: -0.72em;
	margin-left: 0.07em;
}

.page-header-icon img {
	border-radius: 3px;
}

.link-to-page {
	margin: 1em 0;
	padding: 0;
	border: none;
	font-weight: 500;
}

p > .user {
	opacity: 0.5;
}

td > .user,
td > time {
	white-space: nowrap;
}

input[type="checkbox"] {
	transform: scale(1.5);
	margin-right: 0.6em;
	vertical-align: middle;
}

p {
	margin-top: 0.5em;
	margin-bottom: 0.5em;
}

.image {
	border: none;
	margin: 1.5em 0;
	padding: 0;
	border-radius: 0;
	text-align: center;
}

.code,
code {
	background: rgba(135, 131, 120, 0.15);
	border-radius: 3px;
	padding: 0.2em 0.4em;
	border-radius: 3px;
	font-size: 85%;
	tab-size: 2;
}

code {
	color: #eb5757;
}

.code {
	padding: 1.5em 1em;
}

.code-wrap {
	white-space: pre-wrap;
	word-break: break-all;
}

.code > code {
	background: none;
	padding: 0;
	font-size: 100%;
	color: inherit;
}

blockquote {
	font-size: 1.25em;
	margin: 1em 0;
	padding-left: 1em;
	border-left: 3px solid rgb(55, 53, 47);
}

.bookmark {
	text-decoration: none;
	max-height: 8em;
	padding: 0;
	display: flex;
	width: 100%;
	align-items: stretch;
}

.bookmark-title {
	font-size: 0.85em;
	overflow: hidden;
	text-overflow: ellipsis;
	height: 1.75em;
	white-space: nowrap;
}

.bookmark-text {
	display: flex;
	flex-direction: column;
}

.bookmark-info {
	flex: 4 1 180px;
	padding: 12px 14px 14px;
	display: flex;
	flex-direction: column;
	justify-content: space-between;
}

.bookmark-image {
	width: 33%;
	flex: 1 1 180px;
	display: block;
	position: relative;
	object-fit: cover;
	border-radius: 1px;
}

.bookmark-description {
	color: rgba(55, 53, 47, 0.6);
	font-size: 0.75em;
	overflow: hidden;
	max-height: 4.5em;
	word-break: break-word;
}

.bookmark-href {
	font-size: 0.75em;
	margin-top: 0.25em;
}

.sans { font-family: ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol"; }
.code { font-family: "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace; }
.serif { font-family: Lyon-Text, Georgia, ui-serif, serif; }
.mono { font-family: iawriter-mono, Nitti, Menlo, Courier, monospace; }
.pdf .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK JP'; }
.pdf:lang(zh-CN) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK SC'; }
.pdf:lang(zh-TW) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK TC'; }
.pdf:lang(ko-KR) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK KR'; }
.pdf .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.pdf .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK JP'; }
.pdf:lang(zh-CN) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK SC'; }
.pdf:lang(zh-TW) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK TC'; }
.pdf:lang(ko-KR) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK KR'; }
.pdf .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.highlight-default {
	color: rgba(55, 53, 47, 1);
}
.highlight-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.highlight-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.highlight-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.highlight-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.highlight-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.highlight-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.highlight-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.highlight-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.highlight-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.highlight-gray_background {
	background: rgba(241, 241, 239, 1);
}
.highlight-brown_background {
	background: rgba(244, 238, 238, 1);
}
.highlight-orange_background {
	background: rgba(251, 236, 221, 1);
}
.highlight-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.highlight-teal_background {
	background: rgba(237, 243, 236, 1);
}
.highlight-blue_background {
	background: rgba(231, 243, 248, 1);
}
.highlight-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.highlight-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.highlight-red_background {
	background: rgba(253, 235, 236, 1);
}
.block-color-default {
	color: inherit;
	fill: inherit;
}
.block-color-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.block-color-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.block-color-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.block-color-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.block-color-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.block-color-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.block-color-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.block-color-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.block-color-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.block-color-gray_background {
	background: rgba(241, 241, 239, 1);
}
.block-color-brown_background {
	background: rgba(244, 238, 238, 1);
}
.block-color-orange_background {
	background: rgba(251, 236, 221, 1);
}
.block-color-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.block-color-teal_background {
	background: rgba(237, 243, 236, 1);
}
.block-color-blue_background {
	background: rgba(231, 243, 248, 1);
}
.block-color-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.block-color-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.block-color-red_background {
	background: rgba(253, 235, 236, 1);
}
.select-value-color-pink { background-color: rgba(245, 224, 233, 1); }
.select-value-color-purple { background-color: rgba(232, 222, 238, 1); }
.select-value-color-green { background-color: rgba(219, 237, 219, 1); }
.select-value-color-gray { background-color: rgba(227, 226, 224, 1); }
.select-value-color-opaquegray { background-color: rgba(255, 255, 255, 0.0375); }
.select-value-color-orange { background-color: rgba(250, 222, 201, 1); }
.select-value-color-brown { background-color: rgba(238, 224, 218, 1); }
.select-value-color-red { background-color: rgba(255, 226, 221, 1); }
.select-value-color-yellow { background-color: rgba(253, 236, 200, 1); }
.select-value-color-blue { background-color: rgba(211, 229, 239, 1); }

.checkbox {
	display: inline-flex;
	vertical-align: text-bottom;
	width: 16;
	height: 16;
	background-size: 16px;
	margin-left: 2px;
	margin-right: 5px;
}

.checkbox-on {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20width%3D%2216%22%20height%3D%2216%22%20fill%3D%22%2358A9D7%22%2F%3E%0A%3Cpath%20d%3D%22M6.71429%2012.2852L14%204.9995L12.7143%203.71436L6.71429%209.71378L3.28571%206.2831L2%207.57092L6.71429%2012.2852Z%22%20fill%3D%22white%22%2F%3E%0A%3C%2Fsvg%3E");
}

.checkbox-off {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20x%3D%220.75%22%20y%3D%220.75%22%20width%3D%2214.5%22%20height%3D%2214.5%22%20fill%3D%22white%22%20stroke%3D%22%2336352F%22%20stroke-width%3D%221.5%22%2F%3E%0A%3C%2Fsvg%3E");
}
	
</style></head><body><article id="71532f08-be91-4c5b-a334-e7364e0dc013" class="page sans"><header><h1 class="page-title"></h1></header><div class="page-body"><h3 id="eb6c9e80-d540-479f-a6cc-5434a3bef4ab" class="">TRIGGERS</h3><p id="9ca4dcc7-d75f-4499-b345-51f552454752" class="">
</p><p id="601c5bdd-d6d0-4148-8404-66cad4d52976" class=""> The CONNECT_CONSTRAINT trigger is for disabling two users to connect for two times.</p><pre id="cb9a18c3-fdca-4463-9de7-b93acfb18feb" class="code"><code>/*#bir kullanıcının bağlandığı kişi ile tekrar bağlanamamalı*/
/*(a,b) mevcutsa (b,a) mevcut olmamalı*/
DELIMITER $$
CREATE TRIGGER CONNECT_CONSTRAINT
BEFORE INSE
        ON CONNECT
            FOR EACH ROW
                BEGIN
                    IF EXISTS(
                                SELECT * 
                                FROM CONNECT as A 
                                WHERE CONCAT(A.User_ssn,A.Connected_ssn) = CONCAT(NEW.Connected_ssn,NEW.User_ssn))
                            THEN SIGNAL SQLSTATE '45000'
                                    SET MESSAGE_TEXT = 'They are already connected';
                    END IF;                 
                END;
$$</code></pre><p id="ece9938b-7071-4ed6-afde-a1268e47f754" class="">
</p><p id="0e998424-0de5-4ad5-bf75-105c5606f044" class="">The ORGANIZATION_ADMIN_INSERT trigger is for automatically updating WORKS_FOR_ORG table with organization admin.</p><pre id="2d4b65d5-3efe-4d7d-8efb-b6ee802076f6" class="code"><code>DELIMITER $$
/*Eğer bir user bir organizasyonun admini ise orda zaten çalışıyor olmalıdır*/
CREATE TRIGGER ORGANIZATION_ADMIN_INSERT
AFTER INSERT 
             ON ORGANIZATION
                    FOR EACH ROW
                        BEGIN
                            IF NOT EXISTS(
                                            SELECT * 
                                            FROM WORKS_FOR_ORG 
                                            WHERE NEW.Admin_ssn = WORKS_FOR_ORG.User_ssn and WORKS_FOR_ORG.Org_id = NEW.Id )
                                THEN INSERT INTO WORKS_FOR_ORG(User_ssn,Org_id)
                                        VALUES (NEW.Admin_ssn,NEW.Id);
                            END IF;
                        END;
$$</code></pre><p id="465f880b-a355-43b1-a2c4-8da2a50c2b2f" class="">
</p><p id="fe911523-4bca-4d31-b64b-e90e109d963c" class="">The triggers will be activated when user and organization tables have some insertion. Finally, the ACCOUNT table will be updated with the triggers.</p><pre id="397efd53-0a3d-4ae5-88d9-5b9652550ec1" class="code"><code>DEMLIMITTER $$
CREATE TRIGGER USER_ACCOUNT_INSERTION
BEFORE INSERT 
        ON USER 
FOR EACH ROW
            BEGIN
                INSERT INTO ACCOUNT(Account_id)
                VALUES (NEW.Ssn);
            END;
$$

CREATE TRIGGER ORG_ACCOUNT_INSERTION
BEFORE INSERT 
        ON ORGANIZATION 
FOR EACH ROW
            BEGIN
                INSERT INTO ACCOUNT(Account_id)
                VALUES (NEW.Id);
            END;
$$
</code></pre><p id="a0ff6335-cdce-4ecf-b65e-4bd0fcb081fc" class="">
</p><p id="80996715-2a96-4572-b623-6830c4c7c126" class="">The NOPERMISSION_ASG_UPLOAD is for disabling to users who are not enrolled to a specific course which is assignment upload for. </p><pre id="2cb8ab3e-afd3-4256-9e24-c653601889b9" class="code"><code>DELIMITER $$

CREATE TRIGGER NOPERMISSION_ASG_UPLOAD
BEFORE INSERT
        ON ASSIGNMENT_UPLOAD
            FOR EACH ROW
                BEGIN
                    IF NOT EXISTS(
                        SELECT *
                        FROM ASSIGNMENT AS ASG  , ENROLLS AS ENR
                        WHERE NEW.Assignment_id = ASG.Assignment_id 
                                        AND  ASG.Course_id = ENR.Course_id
                                                AND NEW.Student_ssn = ENR.Student_ssn)
                        THEN SIGNAL SQLSTATE '45000'
                                    SET MESSAGE_TEXT = 'No permission to the user. Not enrolled to the course!';
                    END IF;
                END;
$$</code></pre><p id="1268f041-fcd6-405f-940c-0184fd77df62" class="">
</p><p id="020079b3-65dd-4e12-9585-e939b2c09e10" class="">The triggers will be activated when POST,COMMENT and ANSWER tables have some insertion. Finally, the LIKABLE_CONTENT table will be updated with the triggers.</p><pre id="191dbdaa-629d-4173-9622-55d32f422f80" class="code"><code>CREATE TRIGGER LIKABLE_POST_INSERTION
BEFORE INSERT 
        ON POST 
FOR EACH ROW
            BEGIN
                INSERT INTO LIKABLE_CONTENT(Id)
                VALUES (NEW.Likable_content_id);
            END;
$$     

CREATE TRIGGER LIKABLE_COMMENT_INSERTION
BEFORE INSERT 
        ON COMMENT 
FOR EACH ROW
            BEGIN
                INSERT INTO LIKABLE_CONTENT(Id)
                VALUES (NEW.Likable_content_id);
            END;
$$  

CREATE TRIGGER LIKABLE_ANSWER_INSERTION
BEFORE INSERT 
        ON ANSWER 
FOR EACH ROW
            BEGIN
                INSERT INTO LIKABLE_CONTENT(Id)
                VALUES (NEW.Likable_content_id);
            END;
$$</code></pre><p id="2558f3bf-e764-4e43-a47c-f6a72ec4b1cc" class="">
</p><h3 id="00cb635f-7be2-4201-b79b-c68782a57618" class="">CONSTRAINTS-ASSERTIONS</h3><p id="4c8dc2c3-76da-4f4c-b59a-d8ce7faf316a" class="">
</p><p id="beb74b35-6c69-442e-9b33-b2fc83992cba" class="">The SLFCNCTN constraint is for disabling self connection on system.</p><pre id="20ac3ad5-49e0-4992-90bb-b0d72b70dc82" class="code"><code>CREATE TABLE CONNECT(
    User_ssn CHAR(9) NOT NULL,
    Connected_ssn CHAR(9) NOT NULL,
    CONSTRAINT SLFCNCTN CHECK (User_ssn != Connected_ssn),
    **
);</code></pre><p id="0e4990f1-986f-4442-8c1a-a1b71ebef28c" class="">
</p><p id="05e204f8-df00-40b5-9fb5-1aaf8942daba" class="">The CheckEndLaterThanStart constraint is for checking if start and end dates is valid.</p><pre id="7d94aa1e-6e77-4232-8c4e-fcaf20fea612" class="code"><code>CREATE TABLE PROJECT(
    **
    Start_date TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
    End_date TIMESTAMP NULL DEFAULT NULL,
    CONSTRAINT CheckEndLaterThanStart CHECK (End_date=NULL OR End_date &gt;= Start_date),
	  **
);</code></pre><p id="5d522adf-78cb-45b2-b2fa-bd72c62982b9" class="">
</p><p id="1a5e85f3-b742-4d93-930c-156a2c58bda0" class="">The GRADECONSTRAINT constraint is for checking if grade value is valid.</p><pre id="12fdac8a-4bde-4c4d-888e-06a9e3726bf7" class="code"><code>CREATE TABLE ASSIGNMENT_GRADE(
    **
    Grade INTEGER NOT NULL DEFAULT 0,
    CONSTRAINT GRADECONSTRAINT CHECK(Grade&gt;=0 and Grade&lt;=100),
    **
);</code></pre><p id="40ed9060-0993-47f3-b32b-827fa80dcffa" class="">
</p><p id="71871713-5e72-45a1-b9fc-ab4b80696ffc" class="">The NOBADCOMMENT constraint is for disabling swear words to use.</p><pre id="bfae1fdb-3773-482b-bc70-642c1d67afdb" class="code"><code>CREATE TABLE COMMENT(
    **
    Body VARCHAR(255) DEFAULT "Comment_body",
    CONSTRAINT NOBADCOMMENT CHECK(Body NOT LIKE "%fuck%"),
    **
);</code></pre><p id="81ba46a6-4a40-482f-a4c7-1adc45a5b0cf" class="">
</p><p id="fb8e3487-154f-447c-9043-3148b52fce43" class="">The BADCHARS constraint is for disabling unwanted chars to be used!</p><pre id="630033af-2936-4ee3-aa41-efafd09f5a99" class="code"><code>CREATE TABLE USER(
        ***
        name VARCHAR(100) NOT NULL,
        CONSTRAINT BADCHARS CHECK(name LIKE "%*%" 
																							OR name LIKE "%-%" 
																										OR name LIKE "%+%" 
																															OR name LIKE "%~%")
        *** 
    );</code></pre><p id="73074fa4-0ed0-45f4-b156-199e3a59b489" class="">
</p><p id="52295cdf-842f-400a-8712-88d3ace41164" class="">The CONNECT_CONSTRAINT is for disabling repeated connections to occur.</p><pre id="1be3ff9b-e4f7-484b-a834-5e2294e621e5" class="code"><code>DELIMITER $$
CREATE TRIGGER CONNECT_CONSTRAINT
BEFORE INSERT
        ON CONNECT
            FOR EACH ROW
                BEGIN
                    IF EXISTS(
                                SELECT *
                                FROM CONNECT as A
                                WHERE CONCAT(A.User_ssn,A.Connected_ssn) = CONCAT(NEW.Connected_ssn,NEW.User_ssn))
                            THEN SIGNAL SQLSTATE '45000'
                                    SET MESSAGE_TEXT = 'They are already connected';
                    END IF;
                END;
$$</code></pre><h3 id="ce42c223-643f-4139-b878-3534a43672a0" class="">SQL STATEMENTS</h3><ol type="1" id="aaed9f4e-46c4-4991-b29a-fa644976938e" class="numbered-list" start="1"><li>INSERTIONS-DELETIONS-UPDATES<ol type="a" id="5b135d27-573d-475d-b20a-15162b74e279" class="numbered-list" start="1"><li>INSERTIONS<ol type="i" id="cea94753-9992-4e84-bc77-98721b93519e" class="numbered-list" start="1"><li>TABLE USER<pre id="41543026-2d37-4157-8ace-84eac3576841" class="code"><code>INSERT INTO USER (Ssn,title,name,last_logged)
VALUES
  (500000010,"Student","Nissim Deleon","2021-11-22"),
  (500000011,"Data Scientist","Avram Golden","2021-11-22"),
  (500000012,"Teacher","Nayda Rios","2021-11-22"),
  (500000013,"Entrepreneur","Harding Wooten","2021-11-22"),
  (500000014,"Member","Whoopi Lindsay","2021-11-22"),
  (500000015,"Manager","Grant Poole","2021-11-22"),
  (500000016,"Entrepreneur","Stuart Everett","2021-11-22"),
  (500000017,"Doctor","Garrett Rowland","2021-11-22"),
  (500000018,"Prof","Alfreda Reeves","2021-11-22"),
  (500000019,"Entrepreneur","Meredith Cotton","2021-11-22");</code></pre></li></ol><p id="78af1cfa-73f1-416a-919f-4079f070cd5b" class="">  b. TABLE CONNECT</p><div class="indented"><pre id="6f55a631-f5fb-4ac6-b60a-6c7e8f1ab6d7" class="code"><code>INSERT INTO CONNECT (User_ssn,Connected_ssn)
VALUES
  (500000010,500000011),
  (500000010,500000012),
  (500000010,500000013),
  (500000010,500000014),
  (500000010,500000015),
  (500000015,500000016),
  (500000018,500000017),
  (500000005,500000018),
  (500000013,500000012),
  (500000018,500000019);</code></pre></div><p></p><p id="c23c1487-d016-4a3d-9cd4-01a1303dd841" class="">  c. TABLE POST</p><div class="indented"><pre id="365a506f-73fe-4885-9472-fca3bfb0ed39" class="code"><code>INSERT INTO POST(Id,Account_id,Content,Likable_content_id )
VALUES
  (31,500000069,"The system is all about memorization!",900000031),
  (32,500000071,"Engineering harder than anybody think",900000032),
  (33,500000073,"Harder you work luckier you get!",900000033),
  (34,500000075,"It's all about consistency!",900000034),
  (35,500000077,"Life is too short.İf you don't look around sometimes you could miss it.",900000035),
  (37,500000081,"With great power comes great responsibility",900000037);
  </code></pre></div><p></p></li></ol><p id="44263161-cb0a-44d6-a03f-08f0381998d1" class="">
</p><p id="6cf67f41-950e-4572-921a-2532d8384754" class="">b. DELETIONS</p><div class="indented"><ol type="a" id="e52be257-cc43-4ba4-bd1b-049c1e769186" class="numbered-list" start="1"><li>TABLE USER<pre id="f6483add-2199-49b0-b76b-781950ca4b3c" class="code"><code>DELETE FROM USER
WHERE Ssn=500000010;</code></pre></li></ol><ol type="a" id="09bf42b3-3b93-4955-a2fc-b109e9c725a0" class="numbered-list" start="2"><li>TABLE CONNECT<pre id="22526368-1e4b-4684-8b03-53507343df7b" class="code"><code>DELETE FROM CONNECT
WHERE  user_ssn = 500000010
       AND connected_ssn = 500000011;</code></pre></li></ol><ol type="a" id="2f935de6-9c15-46ca-9921-8be2c4f4648f" class="numbered-list" start="3"><li>TABLE POST<pre id="d9d44713-a54f-4055-920b-5a5ae59a80d3" class="code"><code>DELETE FROM POST
WHERE Content LIKE '%fuck%';</code></pre></li></ol><p id="63b08509-7e0f-42a0-aa4a-9e42ac7b8748" class="">
</p></div><p></p><p id="f7c4ad9f-2b15-42cb-b883-ca01e7b4f164" class="">c. UPDATES</p><div class="indented"><ol type="a" id="bfad71f2-cebd-4127-8f39-77cea448dcad" class="numbered-list" start="1"><li>TABLE ASSIGNMENT_GRADE<pre id="2fb80993-9711-4302-a0c9-5c497b8974a1" class="code"><code>UPDATE ASSIGNMENT_GRADE
SET Grade = 90
WHERE Student_ssn =500000086;</code></pre></li></ol><ol type="a" id="9e55ace5-f56c-4ef0-bf2e-4dc713c62ddc" class="numbered-list" start="2"><li>TABLE USER<pre id="a01ee9ea-d05d-47c8-8675-4f50d0e5f148" class="code"><code>UPDATE USER
SET title="Prof"
WHERE Ssn=500000106;</code></pre></li></ol><ol type="a" id="4ced35d1-8c71-4d2b-b17e-b47c14922951" class="numbered-list" start="3"><li>TABLE ORGANIZATION<pre id="75a8433c-0f4a-4cca-a049-e1a1b76d58ba" class="code"><code>UPDATE ORGANIZATION
SET Admin_ssn=500000009
WHERE Id=600000007;</code></pre></li></ol><p id="0da9a059-121b-4468-ac09-001dc9dfc606" class="">
</p><p id="9bef4ac0-c227-4763-84f4-52cbc6c42ee3" class="">2 THE 10 STATEMENTS</p><ol type="a" id="6841cf25-cc6c-4ad4-b42a-77db785d5cd2" class="numbered-list" start="1"><li>Maximum One Table<p id="b551f5e6-6910-482a-a702-46e8c609336c" class="">1.Information of active organizations registered in the system and established after 2000...</p><pre id="0c5c1443-7b2a-4fdd-81d2-52ee30dc181a" class="code"><code>SELECT 
  name, 
  Start_date, 
  Mission, 
  Vision 
FROM 
  ORGANIZATION 
WHERE 
  YEAR(Start_date)&gt; 2000;</code></pre><p id="25e039b2-ddaa-4340-8ad4-d0596f8727ed" class="">
</p><p id="564f9f38-6914-4ec6-bdab-f1cd16791529" class="">2.Posts in the system that contain phone numbers...</p><pre id="7bb28c22-3ad5-4548-8787-813b40365b2d" class="code"><code>SELECT 
  Id, 
  Account_id, 
  Created_at, 
  Content 
FROM 
  POST 
WHERE 
  Content LIKE "%5_________%" 
  OR Content LIKE "%5__ ___ __ __%" 
  OR Content LIKE "%(5__) ___ __ __%";</code></pre><p id="f7510378-8619-46ef-aa50-6e2f7c24a0e6" class="">
</p><p id="58a8eee3-94df-413c-8953-896278833c68" class="">3.Data for comments with content longer than 25 characters...</p><pre id="502a31bc-c6db-44c4-99f5-3013b83631d1" class="code"><code>SELECT 
  Comment_id, 
  Account_id, 
  Body 
FROM 
  COMMENT 
WHERE 
  CHAR_LENGTH(Body) &gt; 25;</code></pre><p id="182cc551-23c8-4f27-8d13-11d8ecd428cc" class="">
</p></li></ol><ol type="a" id="f574b14a-ff24-4628-8383-6e22ee19e072" class="numbered-list" start="2"><li>Minimum Two Tables<p id="5033e143-fab1-48c1-bd01-a88fce4f0683" class="">1.The name of the course that has more than one assignment in the 2020 and the number of how many assignments it has in descending order...</p><pre id="5ed16b0c-e986-45e9-a4fd-aa9a1bdfbbc4" class="code"><code>SELECT 
  C.Cname as Course_Name, 
  COUNT(*) as Ass_Count 
FROM 
  COURSE AS C, 
  ASSIGNMENT AS A 
WHERE 
  C.Id = A.Course_id 
  AND YEAR(C.Cdate)= 2020 
GROUP BY 
  C.Id 
ORDER BY 
  Ass_Count DESC;</code></pre><p id="e64011aa-6f56-467e-ac9a-ce35f7e6f803" class="">
</p><p id="5c4a11a6-23ec-43c7-98e4-e33edb45b5d9" class="">2.Data from teachers teaching Calculus 1.</p><pre id="25ee1a71-5e7f-4c4b-b0a6-e6b0077db8d2" class="code"><code>SELECT 
  U.Ssn, 
  U.name, 
  C.Cdate as Course_date 
FROM 
  COURSE AS C, 
  USER AS U 
WHERE 
  C.Teacher_ssn = U.Ssn 
  AND C.Cname = "Calculus 1";</code></pre><p id="c9029775-404a-4e4d-8a04-cbdc5a18fa9d" class="">
</p><p id="3c742c57-86b0-49a7-8542-9037b3a66b5b" class="">3.Data of most skilled 10 users in descending order</p><pre id="c633d0f4-26b6-4a62-8e0c-b31af354fb67" class="code"><code>SELECT title,
       name,
       last_logged,
       COUNT(*) AS Skill_count
FROM USER,
     USER_SKILLS
WHERE Ssn = User_ssn
GROUP BY Ssn
ORDER BY Skill_count DESC
LIMIT 10;</code></pre><p id="842237e5-fe29-47d6-bd61-1a2cbf374d96" class="">
</p><p id="3df28c90-2f86-495d-8a6f-11c339641b13" class="">4.Let a post list the replies to the comment that received more likes than the comment made.</p><pre id="5b03e660-cde3-4691-9a07-e78aa2ff93a9" class="code"><code>SELECT C.Comment_id,
       AN.Answer_id,
       C.Body AS C_body,
       AN.Body AS A_body
FROM COMMENT AS C,
                ANSWER AS AN
WHERE
    (SELECT COUNT(*)
     FROM LIKES AS L
     WHERE AN.Likable_content_id = L.Likable_content_id
       AND AN.Comment_id = C.Comment_id) &gt;
    (SELECT COUNT(*)
     FROM LIKES AS L
     WHERE L.Likable_content_id = C.Likable_content_id);</code></pre></li></ol><p id="10e267e6-1c1b-4160-bb29-6866cce4e1c0" class="">
</p><p id="5ca80d92-55d3-411a-bd75-fc28be99263f" class="">c. Minimum Three Tables</p><div class="indented"><p id="d57e27a9-670f-4659-bc9f-23e0e1f7322e" class="">1.The data of the projects worked by the users whose grade point average is higher than 50 from the assignments they have uploaded...</p><pre id="763246d8-e16d-4990-a896-8d0b559d1708" class="code"><code>SELECT U.Ssn,
       U.name,
       P.Pname,
       P.Start_date,
       P.End_date
FROM USER AS U,
             WORKS_ON_PROJECT AS WOP,
             PROJECT AS P
WHERE P.Id = WOP.Project_id
  AND WOP.User_ssn = U.Ssn
  AND (U.Ssn) IN
    (SELECT AG.Student_ssn
     FROM ASSIGNMENT_GRADE AS AG
     GROUP BY AG.Student_ssn
     HAVING AVG(AG.Grade)&gt;50) ;</code></pre><p id="076e40f9-5a0b-46c8-aa29-7be10ea9d62e" class="">
</p><p id="d5e919bf-03f6-4427-a373-837666391e16" class="">2.The names,titles and last login dates of the five users with the most connections who have data on moodle ...</p><pre id="647e4a11-3512-404d-bf69-55ce84c893fc" class="code"><code>SELECT U.Name,
       U.title,
       U.last_logged
FROM USER AS U,
             TEACHER AS T,
             STUDENT AS S
WHERE (U.Ssn = T.Ssn
       OR U.SSN = S.Ssn)
  AND U.Ssn IN
    (SELECT U.Ssn
     FROM USER AS U,
                  CONNECT AS C
     WHERE U.Ssn = C.User_ssn
       OR U.Ssn = C.Connected_ssn
     GROUP BY U.Ssn
     ORDER BY Count(*) DESC)
LIMIT 5 ;</code></pre><p id="5ae2bec1-3fe0-479b-8e1b-e4d02ce8e757" class="">
</p><p id="1398a39b-1b5a-4441-9049-56cb6b341ee9" class="">3.Number of assignments submitted and graded by students who enrolled to the most courses...</p><pre id="3b8fa546-adee-4f2f-a937-2fc7b171c16a" class="code"><code>WITH RECURSIVE MOST_ENROLLED_USERS(Ssn, total)AS
  (SELECT U.Ssn,
          COUNT(*) AS total
   FROM STUDENT AS U,
        ENROLLS AS E
   WHERE U.Ssn = E.Student_ssn
   GROUP BY U.Ssn
   UNION SELECT M.Ssn,
                M.total
   FROM MOST_ENROLLED_USERS AS M)
SELECT M.Ssn,
       M.total,
       USER.name,

  (SELECT COUNT(*)
   FROM ASSIGNMENT_UPLOAD AS A
   WHERE A.Student_ssn = M.Ssn) AS uploaded_as ,

  (SELECT COUNT(*)
   FROM ASSIGNMENT_GRADE AS A
   WHERE A.Student_ssn = M.Ssn) AS graded_as
FROM MOST_ENROLLED_USERS AS M,
     USER
WHERE M.Ssn = USER.Ssn
ORDER BY total DESC
LIMIT 5;</code></pre></div><p></p><p id="216c6ad9-54e8-4b13-bf39-6136aae2b8c8" class="">
</p></div><p></p><p id="e8dff91d-4661-4ef7-a738-62453ae24b52" class="">3 THE 5 ORIGINAL STATEMENT</p><p id="05331376-c577-41f1-9d3a-66392acf3414" class=""></p><div class="indented"><p id="28956640-510c-43c3-b594-c33238027c52" class="">1.The number of talents of students who have not uploaded any assignment they are responsible for...</p><pre id="e08517a1-530e-4c68-98fa-aeac529f7482" class="code"><code>SELECT S.Ssn,
       COUNT(*) AS skill_c
FROM STUDENT AS S,
     ASSIGNMENT AS A,
                   USER_SKILLS AS SKILL
WHERE SKILL.User_ssn = S.Ssn
  AND NOT EXISTS
    (SELECT *
     FROM ASSIGNMENT_UPLOAD AS UPLOAD
     WHERE S.Ssn = UPLOAD.Student_ssn )
  AND A.Assignment_id IN
    (SELECT A.Assignment_id
     FROM ENROLLS AS E
     WHERE A.Course_id = E.Course_id
       AND S.Ssn = E.Student_ssn )
GROUP BY SKILL.User_ssn;</code></pre><p id="d416f29e-c7b7-4844-a5c5-3b198d0d69f5" class="">
</p><p id="597fb3d8-cb31-4d9d-ab96-281204b00196" class="">2.Project data including students who enroll in lessons given by teachers who speak more than one language...</p><pre id="a2971e54-b306-47cf-b498-39171500c0b4" class="code"><code>SELECT E.Student_ssn,
       P.Pname,
       P.Pdesc,
       P.Start_date
FROM ENROLLS AS E,
     COURSE AS CRS,
     PROJECT AS P,
     WORKS_ON_PROJECT AS WOP
WHERE WOP.User_ssn = E.Student_ssn
  AND WOP.Project_id = P.Id
  AND CRS.Id IN
    (SELECT CRS.Id
     FROM TEACHER AS T
     WHERE CRS.Teacher_ssn = T.Ssn
       AND T.Ssn IN
         (SELECT T.Ssn
          FROM USER_LANGS AS UL
          WHERE T.Ssn = UL.User_ssn
          GROUP BY T.Ssn
          HAVING COUNT(*)&gt;1) );</code></pre><p id="3ddf5ad9-784d-40ce-af11-027367e32d8c" class="">
</p><p id="c1c35543-f3b0-4256-9d59-d71c31a7f232" class="">3.As a result of the evaluation of the teachers registered in the system based on Assignments, the data of the 5 teachers with the best evaluation...</p><div class="indented"><p id="2e771a97-c5de-4994-bf7c-6756afc08aab" class="">In evaluation:</p><div class="indented"><ul id="d7385041-3d11-4daf-8281-652d4a63dd13" class="bulleted-list"><li style="list-style-type:disc">The time which spend to teacher to evaluate submitted Assignment (Low Good)</li></ul><ul id="5d21dbb0-f59d-4541-96f9-bb5ca81bf462" class="bulleted-list"><li style="list-style-type:disc">Grade point averages of the students in the relevant course (High Good)</li></ul></div><p></p></div><p></p><pre id="08a2f1ca-38fe-4776-9646-3a94296853a0" class="code"><code>SELECT C.Teacher_ssn,
       U.name AS Teacher_name,
       AVG(TIMESTAMPDIFF(HOUR, AU.Upload_date, AG.Grade_date)) AS avg_time,
       AVG(AG.Grade) AS t_avg_grade,
       count(*) AS std_count
FROM ASSIGNMENT_UPLOAD AS AU,
     ASSIGNMENT_GRADE AS AG,
     COURSE AS C,
     USER AS U
WHERE C.Teacher_ssn = U.Ssn
  AND C.Id = AG.Course_id
  AND AU.Assignment_id = AG.Assignment_id
GROUP BY C.Teacher_ssn
ORDER BY t_avg_grade DESC,
         avg_time ASC ;</code></pre><p id="b1cef85c-df32-4b8f-b45f-46c5f353141d" class="">
</p><p id="59478873-2447-4f0c-8dc4-94ca4418a524" class="">4.The data of the teacher of the course that gives more than three Assignment and how many students take this course..</p><pre id="80b184e7-ea28-4ae8-910d-fbc21bc1fe91" class="code"><code>SELECT U.Ssn AS T_ssn,
       U.name AS Tname,
       C.Cname,
       Count(*) AS St_Count
FROM USER AS U,
             COURSE AS C,
             ENROLLS AS E
WHERE C.Teacher_ssn = U.Ssn
  AND C.Id = E.Course_id
  AND C.Id IN
    (SELECT A.Course_id
     FROM ASSIGNMENT AS A,
                        COURSE AS C
     WHERE A.Course_id = C.Id
     GROUP BY A.Course_id
     HAVING COUNT(*)&gt;3)
GROUP BY E.Course_id;</code></pre><p id="b9dac10d-4ee2-46b4-b5ae-41c2b3609b43" class="">
</p><p id="f9608dfe-df15-4e0c-9adc-25997ac1928f" class="">5.The names, titles, average grades, the number of languages they know and the number of talents they have of users with the highest average according to graded assignments.</p><pre id="95e57cd1-7170-45a1-8f99-f3e20f059759" class="code"><code>WITH RECURSIVE AVG_GRADES(Ssn, Avarage_grade) AS
  (SELECT Student_ssn,
          AVG(Grade)
   FROM ASSIGNMENT_GRADE
   GROUP BY Student_ssn
   UNION SELECT AG.Ssn,
                Ag.Avarage_grade
   FROM AVG_GRADES AS AG)
SELECT name,
       title,
       AG.Avarage_grade,

  (SELECT COUNT(*)
   FROM USER_LANGS AS UL
   WHERE UL.User_ssn = AG.Ssn) AS lang_count,

  (SELECT COUNT(*)
   FROM USER_SKILLS AS US
   WHERE US.User_ssn = AG.Ssn) AS skill_count
FROM AVG_GRADES AS AG,
     USER
WHERE USER.Ssn = AG.Ssn
ORDER BY AG.Avarage_grade DESC
LIMIT 5;</code></pre></div><p></p></li></ol></div></article></body></html>
