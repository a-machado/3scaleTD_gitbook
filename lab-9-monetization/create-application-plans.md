## Create the Application Plans

* Go to https://3scale-admin.3scale.{{ book.suffix }}
* Login as admin/admin
* Click on the **APIs** tab.
* Expand the **Products** API.
* Click on the **Application Plans** link.

![](../assets/Selection_386.png)

* Click on the **Create Application Plan** link.

![](../assets/Selection_387.png)

* Enter the following values:
    * **Name**: ProductsPaidPlan
    * **System Name**: products/paid
* Click on the **Create Application Plan** button.   

![](../assets/Selection_388.png)


{% hint style='info' %}
Note that you could also set things like a **Trial Period**, **Setup fee** and **Monthly Cost**
{% endhint %}

* Click on **Publish**.

![](../assets/Selection_389.png)

* Click on the **Settings** tab.
* Check the **Developers can select a plan when creating a new application** checkbox under **Application Plan Changing**.
* Select **Change plan directly**.
* Click on the **Update Service** button.

![](../assets/Selection_486.png)

* Click on the **Application Plans** tab.
* Click on **ProductsPaidPlan**.
* Click on **Pricing** next to **Get All Products**.
* Click on **new pricing rule**.

![](../assets/Selection_392.png)

* Enter the following values:
    * **From**: 1
    * **To**: 5
    * ** Cost per unit**: 2
* Click on the **Create** button.

![](../assets/Selection_411.png)

* Click on **new pricing rule**.
* Enter the following values:
    * **From**: 6
    * **To**: 
    * ** Cost per unit**: 1
* Click on the **Create** button.
* Click on the **Update Application Plan** button.

![](../assets/Selection_394.png)

* Click on the **APIs** tab.
* Expand the **Stock** API.
* Click on **Create Application Plan**.

![](../assets/Selection_395.png)


* Enter the following values:
    * **Name**: Stock Paid Plan
    * **System Name**: stockPaidPlan
    * **Setup Fee**: 10
* Click on the **Create Application Plan** button.

![](../assets/Selection_396.png)

* Click on **Stock Paid Plan**.
* Click on **Pricing**.
* Click on **new pricing rule**.
* Enter the following values:
    * **From**: 1
    * **To**:
    * **Cost per Unit**: 1
* Click on the **Create** button.

![](../assets/Selection_410.png)

* Click on the **Update Application plan** button.
* Click on **Publish**.



