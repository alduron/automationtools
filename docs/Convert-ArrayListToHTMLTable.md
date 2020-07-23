---
external help file: automationtools-help.xml
Module Name: automationtools
online version:
schema: 2.0.0
---

# Convert-ArrayListToHTMLTable

## SYNOPSIS
Converts an array list to a HTML table

## SYNTAX

```
Convert-ArrayListToHTMLTable [-ArrayList] <ArrayList> [[-TableName] <String>] [-AsCustomObject]
 [[-Limit] <Int32>] [<CommonParameters>]
```

## DESCRIPTION
Converts an array list and its data to a HTML table

## EXAMPLES

### EXAMPLE 1
```
Convert-ArrayListToHTMLTable -ArrayList $List -AsCustomObject
```

## PARAMETERS

### -ArrayList
The list that will be converted to a HTML table

```yaml
Type: ArrayList
Parameter Sets: (All)
Aliases:

Required: True
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -TableName
An optional table name to be injected into the data table

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: 2
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AsCustomObject
Return the HTML table as a PSCustomObject

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### -Limit
An upper limit for the maximum amount of records that can be added into the HTML table

```yaml
Type: Int32
Parameter Sets: (All)
Aliases:

Required: False
Position: 3
Default value: 0
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES
Primarily used for AutomationTools internal email functions

## RELATED LINKS
