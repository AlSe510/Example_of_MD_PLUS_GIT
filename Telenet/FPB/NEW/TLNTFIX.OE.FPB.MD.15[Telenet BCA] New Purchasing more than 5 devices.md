## Prerequisites:

1. Create a new unique location (Create new Location (TC)): Copy from Belgium du, 3002 Antwerp du, Kleinebeerstraat du, h. 3
externalId: 1110xxx, where xxx - any random digits or letters
    >[!NOTE] 
    > unique location is required to avoid matching with existing accounts or ongoing orders on OSS level
1. Telenet BCA with created above location and active Voice Pro 2 Go product with any 3 active VOIP Devices (except 'Cisco 8851/61 key expansion module') and 1 disconnected VOIP Devices (except 'Cisco 8851/61 key expansion module')

1. User with '(A) NetCracker - BSS CC TBO' role
---

## Steps:

1. Login to TOMS -> Navigate to BCA from prerequisites
1. Go to <Order Entry> tab → click **[New Sales Order]** → select Distribution Channel = **Telesales** → click **[Create]**
1. Add two VOIP Devices -> add **Panasonic KX-HDV130A02** (with [Tier of CPE] = ‘Basic’)
    >**ER:** Two VOIP Devices are added
1. Fill in required parameters
1. Go to **<Installation & Delivery>** tab
    >**ER:** These Installation options are available: ['Self-Install', 'Business Install']
1. Select any Type of Installation -> Fill in required parameters -> Submit the SO
    >**ER:** SO is Processed
1. Go to <Order Entry> tab → click [New Sales Order] → select Distribution Channel = Telesales → click [Create]
1. Add VOIP Devices -> add Panasonic KX-TGP600 (with [Tier of CPE] = ‘Advanced’)
    >**ER:** VOIP Devices is added
1. Fill in required parameters
1. Go to <Installation & Delivery> tab
    >**ER:** These Installation options are available: ['Business Install']
1. Fill in required parameters -> Submit the SO
    >**ER:** SO is Processed
1. Go to <Order Entry> tab → click [New Sales Order] → select Distribution Channel = Telesales → click [Create]
1. Add VOIP Devices -> add 'Cisco 8851/61 key expansion module'
    >**ER:** VOIP Devices is added
1. Fill in required parameters
1. Go to <Installation & Delivery> tab
    >**ER:** There are no Installation options
1. Fill in required parameters -> Submit the SO
    >**ER:** SO is Processed