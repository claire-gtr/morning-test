HTTP VERBS        CONTROLLERS ACTION         ACTIVE RECORD METHODS
get               index                      .all
get               show                       .find(id)
get               new                        .new()
post              create                     .create(attributes)
get               edit                       .find(id)
patch             update                     .update(attributes)
delete            destroy                    .destroy
