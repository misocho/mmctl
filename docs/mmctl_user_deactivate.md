## mmctl user deactivate

Deactivate users

### Synopsis

Deactivate users. Deactivated users are immediately logged out of all sessions and are unable to log back in.

```
mmctl user deactivate [emails, usernames, userIds] [flags]
```

### Examples

```
  user deactivate user@example.com
  user deactivate username
```

### Options

```
  -h, --help   help for deactivate
```

### Options inherited from parent commands

```
      --format string   the format of the command output [plain, json] (default "plain")
```

### SEE ALSO

* [mmctl user](mmctl_user.md)	 - Management of users

