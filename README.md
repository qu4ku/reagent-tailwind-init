# reagent-tailwind

A starting point with Reagent and Tailwind.

## Setup

### Install dependencies
`npm install`

install npm-run-all to run one command for both shadow and tailwind watch
`npm install -g npm-run-all`

### Watch (dev)
- Shadow: `npm run shadow:watch`
- Tailwind: `npm run tailwind:watch`

- One command: `npm run dev:watch`

### Release (prod)
- Shadow: `npm run shadow:release`
- Tailwind: `npm run tailwind:release`

### Tailwind intellisense support

```
 "tailwindCSS.experimental.classRegex": [                                                       
    ":class\\s+\"([^\"]*)\"",                                                                    
    ":[\\w-.#>]+\\.([\\w-]*)"                                                                    
  ],                                                                                             
  "tailwindCSS.includeLanguages": {                                                              
    "clojure": "html"                                                                            
  }   
```

### References
- https://github.com/jacekschae/shadow-reagent
- https://flaviocopes.com/tailwind-setup/
- https://github.com/tailwindlabs/tailwindcss-intellisense/issues/400#issuecomment-1218494303
