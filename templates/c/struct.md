### {{kind}} `{{name}}` {{anchor refid}}

{{#if basecompoundref}}
```
{{kind}} {{name}}
  {{#each basecompoundref}}
  : {{prot}} {{name}}
  {{/each}}
```  
{{/if}}

{{briefdescription}}

{{detaileddescription}}

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
{{#each filtered.compounds}}{{cell proto}}        | {{cell summary}}
{{/each}}{{#each filtered.members}}{{cell proto}} | {{cell summary}}
{{/each}}
