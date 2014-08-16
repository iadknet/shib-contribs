This is an example attribute resolver to map Active Directory security groups to eduPersonEntitlement attributes.

It contains three attribute resolvers.

The first is a simple resolver for the memberOf AD attribute.

The second is a regex resolver to strip the memberOf attribute down to its basic group name.

The third is a scripted resolver that maps the group membership values into entitlement values within the CSUMB namespace.
