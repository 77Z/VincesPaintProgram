<page actionBarHidden="{true}">
    <label text="Workspace" horizontalAlignment="center" verticalAlignment="middle" stretch="none" />
    <bottomNavigation>

        <!-- The bottom tab UI is created via TabStrip (the containier) and TabStripItem (for each tab)-->
        <tabStrip>
            <tabStripItem>
                <label text="Home" />
                <image src="font://&#xf015;" class="fas t-36" />
            </tabStripItem>
            <tabStripItem class="special">
                <label text="Account" />
                <image src="font://&#xf007;" class="fas t-36" />
            </tabStripItem>
            <tabStripItem class="special">
                <label text="Search" />
                <image src="font://&#xf00e;" class="fas t-36" />
            </tabStripItem>
        </tabStrip>
    
        <!-- The number of TabContentItem components should corespond to the number of TabStripItem components -->
        <tabContentItem>
            <gridLayout>
                <label text="Home Page" class="h2 text-center" />
            </gridLayout>
        </tabContentItem>
        <tabContentItem>
            <gridLayout>
                <label text="Account Page" class="h2 text-center" />
            </gridLayout>
        </tabContentItem>
        <tabContentItem>
            <gridLayout>
                <label text="Search Page" class="h2 text-center" />
            </gridLayout>
        </tabContentItem>
    
    </bottomNavigation>
</page>