# Deploy

Clone the repo - `git clone https://github.com/danifitz/lql-lacework.git`

Enter directory - `cd lql-lacework`

Create the query - `lacework query create -f queries/RB_Custom_Host_Activity_RootLogin.yaml`

Create the policy - `lacework policy create -f policies/rb_custom_rootlogin.yaml`