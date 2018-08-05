---
external help file: PembrokePSsched-help.xml
Module Name: PembrokePSSched
online version:
schema: 2.0.0
---

# Invoke-DeploySched

## SYNOPSIS

## SYNTAX

```
Invoke-DeploySched [[-Destination] <Path>] [[-Source] <Path>] [<CommonParameters>]
```

## DESCRIPTION
Deploy Database Schema to web server.
This needs to be updated

## EXAMPLES

### EXAMPLE 1
```
Invoke-DeploySched -Destination c:\wamp\www\PembrokePS -Source c:\OpenProjects\ProjectPembroke\PembrokePSUI
```

## PARAMETERS

### -Destination
A valid Path is required.

```yaml
Type: Path
Parameter Sets: (All)
Aliases:

Required: False
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Source
A valid Path is required.

```yaml
Type: Path
Parameter Sets: (All)
Aliases:

Required: False
Position: 2
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable.
For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

### System.Boolean

## NOTES
It will create the directory if it does not exist.

## RELATED LINKS
