---
external help file: Microsoft.Azure.PowerShell.Cmdlets.Peering.Common.dll-Help.xml
Module Name: AzureRm.Peering
online version:
schema: 2.0.0
---

# Get-AzureRmPeeringBandwidthOffer

## SYNOPSIS
Gets Bandwidth offers avaliable for a subscription. Applies to both Direct and Partner Peering.

## SYNTAX

### List (Default)
```
Get-AzureRmPeeringBandwidthOffer -ResourceGroupName <String> -PeeringName <String>
 [-DefaultProfile <IAzureContextContainer>] [<CommonParameters>]
```

### single
```
Get-AzureRmPeeringBandwidthOffer -ResourceGroupName <String> -PeeringName <String>
 -OfferName <String> [-DefaultProfile <IAzureContextContainer>] [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureRmPeeringBandwidthOffer** cmdlet gets bandwidth offers for the subscription.

## EXAMPLES

### Example 1
```powershell
PS C:\> Get-AzureRmPeeringBandwidthOffer -ResourceGroupName rg0 -PeeringName MyPeering 
list of offers
```

## PARAMETERS

### -DefaultProfile
The credentials, account, tenant, and subscription used for communication with Azure.

```yaml
Type: IAzureContextContainer
Parameter Sets: (All)
Aliases: AzureRmContext, AzureCredential

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PeeringName
Name of Peering Resource

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -OfferName
Bandwidth offer.
Omit to return all offers

```yaml
Type: String
Parameter Sets: single
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -ResourceGroupName
Resourece Group Name

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### System.String

## OUTPUTS

### Microsoft.Azure.PowerShell.Cmdlets.Peering.Common.Models.PSPeeringBandwidthOffer

## NOTES

## RELATED LINKS