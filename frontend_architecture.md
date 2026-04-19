Role: IT Administrator (Full access to manage inventory and users)

Page: /dashboard (The main landing page after login)

Component: <Sidebar /> - Navigation links (Dashboard, Assets, Users, Assignments).

Component: <TopNavbar /> - Shows logged-in user profile and logout button.

Component: <StatCards /> - 3 blocks showing Total Assets, Deployed Assets, and Broken Assets.

Component: <RecentAssignmentsTable /> - A mini-table showing the last 5 asset assignments.

Page: /inventory (The page to manage all company physical/digital assets)

Component: <Sidebar /> - (Reused from dashboard).

Component: <InventoryDataTable /> - A large table with search, filter, and pagination.

Component: <AddAssetModal /> - A popup form to add a new asset to the DB.

Component: <EditAssetModal /> - A popup form to change asset status (e.g. mark as broken).

Page: /users (The page to manage company employees)

Component: <Sidebar /> - (Reused from dashboard).

Component: <UsersDataTable /> - A large table listing all employees.

Component: <AddUserModal /> - A popup form to onboard a new employee.

Role: Standard Employee (Can only view what is assigned to them)

Page: /my-gear (Their personal landing page)

Component: <TopNavbar /> - (Reused).

Component: <MyAssetList /> - Grid of cards showing assets currently assigned to them.

Component: <ReportIssueButton /> - A button that opens a ticket if their asset is broken or lost.
