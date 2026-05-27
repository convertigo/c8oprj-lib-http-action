
# ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/core/images/project_color_16x16.png?raw=true "Project") lib_HttpAction

{
  "en": "HTTP action plugin for Convertigo No Code Studio to trigger HTTP API calls. This library provides sequences to make HTTP calls with dynamic configuration through requestable variables. It enables No Code Studio users to trigger HTTP API calls without writing code.",
  "fr": "Plugin d'action HTTP pour Convertigo No Code Studio pour déclencher des appels d'API HTTP. Cette bibliothèque fournit des séquences pour effectuer des appels HTTP avec une configuration dynamique via des variables demandables.",
  "it": "Plugin di azione HTTP per Convertigo No Code Studio per attivare chiamate API HTTP. Questa libreria fornisce sequenze per effettuare chiamate HTTP con configurazione dinamica tramite variabili richiedibili.",
  "es": "Complemento de acción HTTP para Convertigo No Code Studio para activar llamadas a API HTTP. Esta biblioteca proporciona secuencias para realizar llamadas HTTP con configuración dinámica a través de variables solicitables.",
  "ch": "适用于Convertigo No Code Studio的HTTP动作插件，用于触发HTTP API调用。该库提供序列以通过请求变量进行动态配置来制作HTTP调用。它使No Code Studio用户能够在无需编写代码的情况下触发HTTP API调用。"
}

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
  "en": "Request body content from sequence variable forms_Body.",
  "fr": "Contenu du corps de la requête depuis la variable de séquence forms_Body.",
  "it": "Contenuto del body della richiesta dalla variabile di sequenza forms_Body.",
  "es": "Contenido del cuerpo de la solicitud desde la variable de secuencia forms_Body.",
  "ch": "来自序列变量forms_Body的请求正文内容。"
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
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/variables/images/variable_color_16x16.png?raw=true "  alt="RequestableHttpVariable" >&nbsp;forms_Headers
</td>
<td>
{
  "en": "HTTP headers from sequence variable forms_Headers.",
  "fr": "En-têtes HTTP depuis la variable de séquence forms_Headers.",
  "it": "Header HTTP dalla variabile di sequenza forms_Headers.",
  "es": "Encabezados HTTP desde la variable de secuencia forms_Headers.",
  "ch": "来自序列变量forms_Headers的HTTP标头。"
}
</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/variables/images/variable_color_16x16.png?raw=true "  alt="RequestableHttpVariable" >&nbsp;forms_Verb
</td>
<td>
HTTP verb supplied by forms_Verb.
</td>
</tr>
</table>

</p></blockquote></details>
</p></blockquote></details>

<details><summary><span style="color:DarkGoldenRod"><i>Sequences</i></span></summary><blockquote><p>


## ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/sequences/images/genericsequence_color_16x16.png?raw=true "GenericSequence") forms_HttpCall

{
  "en": "Triggers HTTP API calls with dynamic verb, body, headers and URL. This sequence allows you to make HTTP requests to any API endpoint with configurable parameters passed as requestable variables.",
  "fr": "Déclenche des appels d'API HTTP avec verbe, corps, en-têtes et URL dynamiques. Cette séquence vous permet d'effectuer des requêtes HTTP vers n'importe quel point de terminaison API avec des paramètres configurables passés en variables demandables.",
  "it": "Attiva chiamate API HTTP con verbo, body, header e URL dinamici. Questa sequenza consente di effettuare richieste HTTP a qualsiasi endpoint API con parametri configurabili passati come variabili richiedibili.",
  "es": "Activa llamadas a API HTTP con verbo, cuerpo, encabezados y URL dinámicos. Esta secuencia permite realizar solicitudes HTTP a cualquier endpoint de API con parámetros configurables pasados como variables solicitables.",
  "ch": "使用动态动词、正文、标头和URL触发HTTP API调用。此序列允许您向任何API端点发送HTTP请求，配置参数通过请求变量传递。"
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
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/variables/images/variable_color_16x16.png?raw=true "  alt="RequestableVariable" >&nbsp;forms_Body
</td>
<td>
{
  "en": "JSON body to send with the request (for POST, PUT, PATCH verbs). This should be a valid JSON string that will be sent as the request payload.",
  "fr": "Corps JSON à envoyer avec la requête (pour les verbes POST, PUT, PATCH). Cela doit être une chaîne JSON valide qui sera envoyée comme charge utile de la requête.",
  "it": "Corpo JSON da inviare con la richiesta (per i verbi POST, PUT, PATCH). Deve essere una stringa JSON valida che verrà inviate come payload della richiesta.",
  "es": "Cuerpo JSON para enviar con la solicitud (para los verbos POST, PUT, PATCH). Esto debe ser una cadena JSON válida que se enviará como carga útil de la solicitud.",
  "ch": "要随请求发送的JSON正文（用于POST、PUT、PATCH动词）。这应该是一个有效的JSON字符串，将作为请求负载发送。"
}
</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/variables/images/variable_color_16x16.png?raw=true "  alt="RequestableVariable" >&nbsp;forms_Headers
</td>
<td>
{
  "en": "JSON array of object headers to include in the request. Format: [{name: Header-Name, value: Header-Value}]. Each object in the array represents a single HTTP header with 'name' and 'value' properties.",
  "fr": "Tableau JSON d'objets d'en-têtes à inclure dans la requête. Format : [{name: Nom-EnTete, value: Valeur-EnTete}]. Chaque objet du tableau représente un en-tête HTTP unique avec les propriétés 'name' et 'value'.",
  "it": "Array JSON di oggetti header da includere nella richiesta. Formato: [{name: Nome-Header, value: Valore-Header}]. Ogni oggetto nell'array rappresenta un singolo header HTTP con le proprietà 'name' e 'value'.",
  "es": "Matriz JSON de objetos de encabezados para incluir en la solicitud. Formato: [{name: Nombre-Encabezado, value: Valor-Encabezado}]. Cada objeto en la matriz representa un encabezado HTTP único con las propiedades 'name' y 'value'.",
  "ch": "要包含在请求中的JSON头对象数组。格式：[{"name": "头名称", "value": "头值"}]。数组中的每个对象代表一个带有'name'和'value'属性的HTTP头。"
}
</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/variables/images/variable_color_16x16.png?raw=true "  alt="RequestableVariable" >&nbsp;forms_Url
</td>
<td>
{
  "en": "URL to call (including optional query string). This is the target endpoint for the HTTP request.",
  "fr": "URL à appeler (incluant la chaîne de requête éventuelle). Il s'agit du point de terminaison cible pour la requête HTTP.",
  "it": "URL da chiamare (inclusa l'eventuale stringa di query). Questo è l'endpoint di destinazione per la richiesta HTTP.",
  "es": "URL a llamar (incluyendo la cadena de consulta opcional). Este es el endpoint de destino para la solicitud HTTP.",
  "ch": "要调用的URL（包括可选的查询字符串）。这是HTTP请求的目标端点。"
}
</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/variables/images/variable_color_16x16.png?raw=true "  alt="RequestableVariable" >&nbsp;forms_Verb
</td>
<td>
{
  "en": "HTTP verb to use (GET, POST, PUT, DELETE, PATCH, etc.). This determines the type of HTTP request to make.",
  "fr": "Verbe HTTP à utiliser (GET, POST, PUT, DELETE, PATCH, etc.). Cela détermine le type de requête HTTP à effectuer.",
  "it": "Verbo HTTP da utilizzare (GET, POST, PUT, DELETE, PATCH, ecc.). Questo determina il tipo di richiesta HTTP da effettuare.",
  "es": "Verbo HTTP a usar (GET, POST, PUT, DELETE, PATCH, etc.). Esto determina el tipo de solicitud HTTP a realizar.",
  "ch": "要使用的HTTP动词（GET、POST、PUT、DELETE、PATCH等）。这决定了要制作的HTTP请求类型。"
}
</td>
</tr>
</table>

</p></blockquote></details>
