
# ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/core/images/project_color_16x16.png?raw=true "Project") lib_HttpAction

HTTP action plugin for Convertigo No Code Studio to trigger HTTP API calls. This library provides actions to make HTTP calls with dynamic configuration through requestable variables. It enables No Code Studio users to trigger HTTP API calls without writing code.

<details><summary><span style="color:DarkGoldenRod"><i>Connectors</i></span></summary><blockquote><p>


## ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/connectors/images/httpconnector_color_16x16.png?raw=true "HttpConnector") HTTP_connector



<details><summary><span style="color:DarkGoldenRod"><i>Transactions</i></span></summary><blockquote><p>


### ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/transactions/images/jsonhttptransaction_color_16x16.png?raw=true "JsonHttpTransaction") HttpCall

{
  "en": "Generic HTTP call transaction for JSON APIs. Uses dynamic URL, verb, body and headers from sequence variables.",
  "fr": "Transaction d'appel HTTP générique pour les API JSON. Utilise l'URL, le verbe, le corps et les en-têtes dynamiques depuis les variables de la séquence.",
  "it": "Transazione di chiamata HTTP generica per API JSON. Utilizza URL, verbo, body e header dinamici dalle variabili della sequenza.",
  "es": "Transacción de llamada HTTP genérica para APIs JSON. Utiliza URL, verbo, body y encabezados dinámicos desde las variables de la secuencia.",
  "ch": "通用JSON API的HTTP调用事务。使用来自序列变量的动态URL、动词、正文和标头。"
}

<span style="color:DarkGoldenRod">Variables</span>

<table>
<tr>
<th>
name
</th>
<th>
comment
</th>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/variables/images/variable_color_16x16.png?raw=true "  alt="RequestableHttpVariable" >&nbsp;__body
</td>
<td>
{
  "en": "Request body content from sequence variable forms_http_body.",
  "fr": "Contenu du corps de la requête depuis la variable de séquence forms_http_body.",
  "it": "Contenuto del body della richiesta dalla variabile di sequenza forms_http_body.",
  "es": "Contenido del cuerpo de la solicitud desde la variable de secuencia forms_http_body.",
  "ch": "来自序列变量forms_http_body的请求正文内容。"
}
</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/variables/images/variable_color_16x16.png?raw=true "  alt="RequestableHttpVariable" >&nbsp;__contentType
</td>
<td>
Resolved request body content type.
</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/variables/images/variable_color_16x16.png?raw=true "  alt="RequestableHttpVariable" >&nbsp;forms_http_headers
</td>
<td>
{
  "en": "HTTP headers from sequence variable forms_http_headers.",
  "fr": "En-têtes HTTP depuis la variable de séquence forms_http_headers.",
  "it": "Header HTTP dalla variabile di sequenza forms_http_headers.",
  "es": "Encabezados HTTP desde la variable de secuencia forms_http_headers.",
  "ch": "来自序列变量forms_http_headers的HTTP标头。"
}
</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/variables/images/variable_color_16x16.png?raw=true "  alt="RequestableHttpVariable" >&nbsp;forms_http_verb
</td>
<td>
HTTP verb supplied by forms_http_verb.
</td>
</tr>
</table>

</p></blockquote></details>
</p></blockquote></details>

<details><summary><span style="color:DarkGoldenRod"><i>Sequences</i></span></summary><blockquote><p>


## ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/sequences/images/genericsequence_color_16x16.png?raw=true "GenericSequence") forms_HttpCall

<div>Triggers an <b>HTTP API call</b> with a dynamic URL, verb, headers and JSON body.</div>

<span style="color:DarkGoldenRod">Variables</span>

<table>
<tr>
<th>
name
</th>
<th>
comment
</th>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/variables/images/variable_color_16x16.png?raw=true "  alt="RequestableVariable" >&nbsp;forms_http_body
</td>
<td>
<div>JSON body to send with the request. Example: 

```
{"name":"Alice","active":true,"tags":["lead","demo"]}
```

. <i>(optional)</i></div>
</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/variables/images/variable_color_16x16.png?raw=true "  alt="RequestableVariable" >&nbsp;forms_http_headers
</td>
<td>
<div>JSON array of HTTP headers. Example: 

```
[{"name":"Accept","value":"application/json"},{"name":"Authorization","value":"Bearer YOUR_TOKEN"}]
```

. <i>(optional)</i></div>
</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/variables/images/variable_color_16x16.png?raw=true "  alt="RequestableVariable" >&nbsp;forms_http_url
</td>
<td>
<div>Target URL to call, including the optional query string. Examples: 

```
https://api.example.com/customers?status=active&amp;limit=10
```

, 

```
https://postman-echo.com/get?search=convertigo&amp;page=1
```

. <i>(mandatory)</i></div>
</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/variables/images/variable_color_16x16.png?raw=true "  alt="RequestableVariable" >&nbsp;forms_http_verb
</td>
<td>
<div>HTTP method to use for the request. Examples: 

```
GET
```

, 

```
POST
```

, 

```
PUT
```

, 

```
PATCH
```

 or 

```
DELETE
```

.</div>
</td>
</tr>
</table>

</p></blockquote></details>
