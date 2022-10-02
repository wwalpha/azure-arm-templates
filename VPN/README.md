# Azure Client VPN

## Steps

1. create vnet
2. create gateway subnet
3. create virtual gateway network
4. create enterprise application of azure vpn client
https://login.microsoftonline.com/common/oauth2/authorize?client_id=41b23e61-6c1e-4545-b367-cd054e0ed4b4&response_type=code&redirect_uri=https://portal.azure.com&nonce=1234&prompt=admin_consent
5. assign user to azure vpn client
6. configure point-to-site
7. donwload vpn client(configuration xml)
8. connect to vpn via azure vpn client

## Parameters

publicIPAddresses_vpn_ip_name: vpn-ip
virtualNetworks_vpn_vnet_name: vpn-vnet
virtualNetworkGateways_vpn_gw_name: vpn-gw
tenant_id: https://login.microsoftonline.com/{add_tenant_id}/
audience: 41b23e61-6c1e-4545-b367-cd054e0ed4b4
issuer: https://sts.windows.net/{add_tenant_id}/