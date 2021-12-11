# Start With CDN

### CSS Style

You know the usage, here's without further ado.

```
<link rel="stylesheet" href="https://hercs.art/cdn/typogrid.css">
```

### Variables

預設的設定值可以讓你無須設定直接套入網頁中。

```
<link rel="stylesheet" href="https://hercs.art/cdn/variable.css">
```

### Javascript Module

你可以使用CDN外部連結檔案來輕鬆使用Typogrid，無須Package你的專案。只要將以下代碼加入你的網頁下方`<Script>`中：

```
<script type="module">
    import {typogrid} from 'https://hercs.art/cdn/typogrid.js';
    typogrid();

</script>
```

請注意，如果要自行編寫的話，請記得要在`<Script>`中加入模組化`module`的`type`，才能讓模塊Javascript正確地被導入。

詳細用法與運作可查閱[關於模組化Javascript的文件](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules)。
