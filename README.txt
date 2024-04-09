Hello GPG

gpg --full-generate-key
gpg --armor --export {key_id}
git config --global user.signingkey {key_id}
git config --global commit.gpgsign true
