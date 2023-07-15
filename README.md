# vs-code-font

Font-Family = "Cascadia Code",
Download link = "https://github.com/microsoft/cascadia-code/releases/tag/v2111.01",
Setting.json =>
"editor.fontFamily": "'Cascadia Code'",
"editor.fontLigatures": "'ss01', 'ss02', 'ss03', 'ss04', 'ss05', 'ss06', 'zero', 'onum'",
"editor.fontWeight": "600",
"editor.tokenColorCustomizations": {
"textMateRules": [
{
"scope": [
"comment",
"constant",
"emphasis",
"entity",
"invalid",
"keyword",
"markup",
"meta",
"storage",
"string",
"strong",
"support",
"variable"
],
"settings": {
"fontStyle": "italic"
}
},
{
"scope": "keyword.other.dotenv",
"settings": {
"foreground": "#FF000000"
}
}
]
},
