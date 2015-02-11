# github-helpers

Helper scripts for working with GitHub.

To use this you need to get a token from GitHub and set it in your global git config.

    git config --global github-helpers.token YOUR-TOKEN

## edit-repository-notifications

Finds all repositories you have access to and all repositories you are subscribed to and makes a long list. The list will be loaded into an editor where you can change the subscriptions. (Just change the 'S' (subscribed) into 'U' (unsubscribed). Once you quit the editor the script will update the subscriptions according to your changes.

