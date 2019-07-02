# Bendera
The Bendera component lets you manage your on-site advertisement. Add advertisements to your front-end and display advertisements based on contexts, templates, resources or advertisement types.

## Usage
```
[[!bendera? 
    &types=`image`
    &limit=`10`
]]
```

## Properties
| Property      | Description                                                   | Example        |
|---------------|---------------------------------------------------------------|----------------|
| tpl           | Chunk to use for rendering item output.                       | benderaItem    |
| wrapperTpl    | Chunk to use for rendering output.                            | benderaWrapper |
| limit         | Limit amount of advertisements to output                      | 1              |
| sortBy        | Sort ads by specific field                                    | startdate      |
| sortDir       | Sort direction                                                | asc            |
| toPlaceholder | Placeholder to use to render output to                        | bendera        |
| types         | Comma delimited list of types to filter advertisements on.    | image,text     |
| contexts      | Comma delimited list of contexts to filter advertisements on. | web,de         |     |

# Free Extra
This is a free extra and the code is publicly available for you to change. The extra is being actively maintained and you're free to put in pull requests which match our roadmap. Please create an issue if the pull request differs from the roadmap so we can make sure we're on the same page.

Need help? [Approach our support desk for paid premium support.](mailto:service@sterc.com)
