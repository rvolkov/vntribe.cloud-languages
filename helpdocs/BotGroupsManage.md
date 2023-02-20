ere you build request to "Groups Management" service. This service allow you to create
        group and assign first gateway user. Groups are full-mesh connected users and they use gateway users to
        send Requests to Services, supported in other groups. Gateway users are able to review/approve requests.
        With groups we implement security and access levels - i.e. "adm" group has administrative Services to control users, groups,
        services and bots. People in "adm" group can send Requests to these services. People in other group should have their
        requests to admin services approved by gateway users. So access level to resources defined by position in topology.
        Messages (Requests/Responses) are travel through groups by Shortest-Path dynamic algorithm.