# random-password-generator
A simple password generator.
To generate password it uses all combinations like like Uppercase, lowercase letters, numbers and special characters.

    from password_generator import robust

    # generate password, by default length will be 8
    print(robust.password_generator())

    # now length will be 10
    print(robust.password_generator(10))
