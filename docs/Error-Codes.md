# Error Codes

| Code | HTTP Status               | Message                                                             | Exception Name                               |
| ---- | ------------------------- | ------------------------------------------------------------------- | -------------------------------------------- |
| 04   | 404-NOT_FOUND             | Data not found : ApiErrorException()                                | ArticleNotFoundException                     |
| 04   | 404-NOT_FOUND             | Brand not found                                                     | BrandNotFoundException                       |
| 04   | 404-NOT_FOUND             | Data not found : ApiErrorException()                                | DataNotFoundException                        |
| 04   | 404-NOT_FOUND             | Role does not exist                                                 | RoleDoesNotExistException                    |
| 04   | 404-NOT_FOUND             | User group not found                                                | UserGroupNotFoundException                   |
| 04   | 404-NOT_FOUND             | User scope not found                                                | UserScopeNotFoundException                   |
| 06   | 400-BAD_REQUEST           | User Scope is invalid                                               | InvalidUserScopeException                    |
| 06   | 400-BAD_REQUEST           | Missing branch                                                      | MissingBranchException                       |
| 06   | 400-BAD_REQUEST           | Missing brand                                                       | MissingBrandException                        |
| 06   | 400-BAD_REQUEST           | Missing partner                                                     | MissingPartnerException                      |
| 06   | 400-BAD_REQUEST           | Missing require field                                               | MissingRequireFieldException                 |
| 07   | 422-UNPROCESSABLE_ENTITY  | Brand name is duplicated                                            | DuplicateBrandNameException                  |
| 07   | 409-CONFLICT              | String? : ApiErrorException()                                       | KeycloakConflictException                    |
| 07   | 422-UNPROCESSABLE_ENTITY  | Branch already created                                              | BranchAlreadyCreatedException                |
| 07   | 422-UNPROCESSABLE_ENTITY  | Branch cannot relate under it's own Mall                            | BranchCannotInItsMallException               |
| 07   | 422-UNPROCESSABLE_ENTITY  | Brand already created                                               | BrandAlreadyCreatedException                 |
| 07   | 422-UNPROCESSABLE_ENTITY  | Branch code is duplicated                                           | DuplicateBranchCodeException                 |
| 07   | 422-UNPROCESSABLE_ENTITY  | Branch name is duplicated                                           | DuplicateBranchNameException                 |
| 07   | 422-UNPROCESSABLE_ENTITY  | Brand code is duplicated                                            | DuplicateBrandCodeException                  |
| 07   | 422-UNPROCESSABLE_ENTITY  | Company name is duplicated                                          | DuplicateCompanyNameException                |
| 07   | 422-UNPROCESSABLE_ENTITY  | Partner code is duplicated                                          | DuplicatePartnerException                    |
| 07   | 422-UNPROCESSABLE_ENTITY  | Username is duplicated                                              | DuplicateUsernameException                   |
| 07   | 422-UNPROCESSABLE_ENTITY  | Partner already created                                             | PartnerAlreadyCreatedException               |
| 07   | 422-UNPROCESSABLE_ENTITY  | Service already applied                                             | ServiceAlreadyAppliedException               |
| 08   | 422-UNPROCESSABLE_ENTITY  | Company ID is invalid                                               | CompanyNotFoundException                     |
| 10   | 422-UNPROCESSABLE_ENTITY  | Cannot delete brand(s)                                              | CannotDeleteBrandException                   |
| 10   | 422-UNPROCESSABLE_ENTITY  | Invalid Company Status                                              | InvalidCompanyStatus                         |
| 10   | 422-UNPROCESSABLE_ENTITY  | Status Already Active                                               | StatusAlreadyActiveException                 |
| 10   | 422-UNPROCESSABLE_ENTITY  | Status Is Not Active                                                | StatusIsNotActiveException                   |
| 10   | 422-UNPROCESSABLE_ENTITY  | User scope is missing                                               | UserScopeIsMissingException                  |
| 11   | 422-UNPROCESSABLE_ENTITY  | Partner code not belong to this $field                              | PartnerCodeNotBelongException                |
| 12   | 400-BAD_REQUEST           | Invalid content length : ApiErrorException()                        | InvalidContentLengthException                |
| 12   | 400-BAD_REQUEST           | Invalid Request Parameter(s) : ApiErrorException()                  | ParameterInvalidException                    |
| 12   | 422-UNPROCESSABLE_ENTITY  | Cannot upload ${if (key.isNullOrBlank()) "content" else key} to AWS | AwsInvalidEntityException                    |
| 12   | 422-UNPROCESSABLE_ENTITY  | Cannot delete The 1 company                                         | CannotDeleteThe1CompanyException             |
| 12   | 422-UNPROCESSABLE_ENTITY  | Cannot $function $secondary With Current $primary Status            | CannotFunctionWithCurrentStatusException     |
| 12   | 422-UNPROCESSABLE_ENTITY  | Cannot Update When Status is draft                                  | CannotUpdateStatusWhenStatusIsDraftException |
| 12   | 422-UNPROCESSABLE_ENTITY  | Cannot Update $field to ${statusMap\[status\]} Status               | CannotUpdateToPreferredStatusException       |
| 12   | 422-UNPROCESSABLE_ENTITY  | Cannot Update $secondary With Current $primary Status               | CannotUpdateWithCurrentStatusException       |
| 12   | 404-NOT_FOUND             | Branch status is invalid                                            | InvalidBranchStatusException                 |
| 12   | 422-UNPROCESSABLE_ENTITY  | Cannot Create Brand With Current Partner Status                     | InvalidPartnerStatusException                |
| 12   | 422-UNPROCESSABLE_ENTITY  | Partner code was deleted                                            | PartnerDeletedException                      |
| 12   | 400-BAD_REQUEST           | The requested company, brand, and branch are not related            | UnrelatedCompanyBrandBranchException         |
| 13   | 422-UNPROCESSABLE_ENTITY  | Cannot Update Status to Draft                                       | CannotUpdateStatusToDraftException           |
| 41   | 403-FORBIDDEN             | Access Denied                                                       | AccessDeniedException                        |
| 44   | 422-UNPROCESSABLE_ENTITY  | Unable to Delete                                                    | UndeletableException                         |
| 45   | 401-UNAUTHORIZED          | Unauthorized                                                        | UnauthorizedException                        |
| 45   | 401-UNAUTHORIZED          | Cannot assign role(s) with selected User Type                       | CannotAssignRoleException                    |
| 45   | 401-UNAUTHORIZED          | Cannot $action partner by CG User                                   | CannotCreateUpdatePartnerException           |
| 45   | 401-UNAUTHORIZED          | Cannot $action this user with $userType type. $detail               | CannotCreateUpdateUserWithThisTypeException  |
| 45   | 401-UNAUTHORIZED          | Invalid user group                                                  | InvalidUserGroupException                    |
| 50   | 502-BAD_GATEWAY           | Bad Gateway : ApiErrorException()                                   | ArticleErrorException                        |
| 50   | 500-INTERNAL_SERVER_ERROR | There's something wrong. Please try again later                     | InternalErrorException                       |
