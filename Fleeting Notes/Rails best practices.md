csfr token error handling = instead of using skip_before_authenticity_token? why not try 
"protect_from_forgery with: :exception". don't put them in quotes.

join tables are used to create a many to many relationsip between models and they are created with the rails g migration CreateJoinTableUsersGroups users groups

"find" searches using a foreign key and that is why find usually goes with params[:id] but "find_by" searches by the parameters it was given for example find_by :email