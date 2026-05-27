


# lib_HttpAction

HTTP action plugin for Convertigo No Code Studio to trigger HTTP API calls. This library provides actions to make HTTP calls with dynamic configuration through requestable variables. It enables No Code Studio users to trigger HTTP API calls without writing code.


For more technical informations : [documentation](./project.md)

- [Installation](#installation)
- [Sequences](#sequences)
    - [forms_HttpCall](#forms_httpcall)


## Installation

1. In your Convertigo Studio click on ![](https://github.com/convertigo/convertigo/blob/develop/eclipse-plugin-studio/icons/studio/project_import.gif?raw=true "Import a project in treeview") to import a project in the treeview
2. In the import wizard

   ![](https://github.com/convertigo/convertigo/blob/develop/eclipse-plugin-studio/tomcat/webapps/convertigo/templates/ftl/project_import_wzd.png?raw=true "Import Project")
   
   paste the text below into the `Project remote URL` field:
   <table>
     <tr><td>Usage</td><td>Click the copy button at the end of the line</td></tr>
     <tr><td>To contribute</td><td>

     ```
     lib_HttpAction=https://github.com/convertigo/c8oprj-lib-http-action.git:branch=master
     ```
     </td></tr>
     <tr><td>To simply use</td><td>

     ```
     lib_HttpAction=https://github.com/convertigo/c8oprj-lib-http-action/archive/master.zip
     ```
     </td></tr>
    </table>
3. Click the `Finish` button. This will automatically import the __lib_HttpAction__ project


## Sequences

### forms_HttpCall

<div>Triggers an <b>HTTP API call</b> with a dynamic URL, verb, headers and JSON body.</div>

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>forms_http_body</td><td><div>JSON body to send with the request. Example: 

```
{"name":"Alice","active":true,"tags":["lead","demo"]}
```

. <i>(optional)</i></div></td>
</tr>
<tr>
<td>forms_http_headers</td><td><div>JSON array of HTTP headers. Example: 

```
[{"name":"Accept","value":"application/json"},{"name":"Authorization","value":"Bearer YOUR_TOKEN"}]
```

. <i>(optional)</i></div></td>
</tr>
<tr>
<td>forms_http_url</td><td><div>Target URL to call, including the optional query string. Examples: 

```
https://api.example.com/customers?status=active&amp;limit=10
```

, 

```
https://postman-echo.com/get?search=convertigo&amp;page=1
```

. <i>(mandatory)</i></div></td>
</tr>
<tr>
<td>forms_http_verb</td><td><div>HTTP method to use for the request. Examples: 

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

.</div></td>
</tr>
</table>



