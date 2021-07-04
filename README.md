# test-autotest-java


public RegistrationPage setEmail(String email){
    emailField.sendKeys(email);
    return this;
}
public RegistrationPage setUsername(String username){
    usernameField.sendKeys(username);
    return this;
}
public RegistrationPage setPassword(String password){
    passwordField.sendKeys(password);
    return this;
}
public RegistrationPage setInvite(String invite){
    inviteField.sendKeys(invite);
    return this;
}
public RegistrationPage setDogovor() {
    if(!dogovorCheckbox.isSelected()) {
        dogovorCheckbox.click();
    }
    return this;
}
public RegistrationPage setPersonal() {
    if(!persCheckbox.isSelected()) {
        persCheckbox.click();
    }
    return this;
}
public void clickSubmitButton() {
    submitButton.click();
}
