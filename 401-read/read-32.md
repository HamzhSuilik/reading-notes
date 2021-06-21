# Permissions

permissions determine whether a request should be granted or denied access. Permission checks are always run at the very start of the view, before any other code is allowed to proceed

Permissions in REST framework are always defined as a list of permission classes

Expected responses to a request for permission:

403 Forbidden  : When the permissions checks fail
— An HTTP 403 Forbidden : The request was successfully authenticated, but permission was denied.
— An HTTP 403 Forbidden : The request was not successfully authenticated, and the highest priority authentication class does not use
— An HTTP 401 Unauthorized : The request was not successfully authenticated, and the highest priority authentication class does use

To change the permission policy settings use the DEFAULT_PERMISSION_CLASSES setting in setting file , The default setting allows anyone to access .

Permissions modes :
API Reference : The AllowAny permission class will allow unrestricted access, regardless of if the request was authenticated or unauthenticated.
The IsAdminUser permission class will deny permission to any user, unless user.is_staff is True in which case permission will be allowed.
IsAuthenticatedOrReadOnly
DjangoModelPermissions

