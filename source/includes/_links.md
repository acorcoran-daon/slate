
## Links

Many IdentityX resources are related to other resources and contain links to them in their response properties. A link property is a nested object that contains an href attribute which is the fully qualified location URI of the linked resource. For example, a <code>IDCheck</code> has an associated <code>User</code>, <code>Documents</code>, <code>Faces</code> etc., and the JSON representation of a registration would contain two link properties such as in the example below:

```JSON
{

}
```
                        
The user link above is referred to as Instance links, as they refer to a specific instance of another resource. The other type of link is a Collection link which is the location of a related collection of resources, for example, the IDCheck request related to a specific user. In this scenario, the user representation below would have an authenticationRequests link attribute:

```JSON
{
  
}
```
                        
Many of these links can be expanded in-line via a request parameter - see Expanding Resources below.
