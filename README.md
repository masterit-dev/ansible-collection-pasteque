# Pasteque Collection

This repo contains the `masterit_dev.pasteque` Ansible Collection.

## Included content

The collection includes 2 roles :
- [masterit_dev.pasteque_api](https://galaxy.ansible.com/masterit_dev/pasteque_api)
- [masterit_dev.pasteque_jsadmin](https://galaxy.ansible.com/masterit_dev/pasteque_jsadmin)

Please check the included content on the [Ansible Galaxy page for this collection](https://galaxy.ansible.com/masterit_dev/pasteque)

## External requirements

Some roles require external libraries. Please check the requirements for each role you use in the role documentation to find out which requirements are needed.

All roles in this collections needs (at least):
- [geerlingguy.php](https://galaxy.ansible.com/geerlingguy/php)
- [geerlingguy.apache](https://galaxy.ansible.com/geerlingguy/apache)
- [geerlingguy.apache-php-fpm](https://galaxy.ansible.com/geerlingguy/apache-php-fpm)
- [geerlingguy.composer](https://galaxy.ansible.com/geerlingguy/composer)

## Using this collection

Before using the pasteque collection, you need to install the collection with the `ansible-galaxy` CLI:

    ansible-galaxy collection install masterit_dev.pasteque

You can also include it in a `requirements.yml` file and install it via `ansible-galaxy collection install -r requirements.yml` using the format:

```yaml
collections:
  - name: masterit_dev.pasteque
```

See [Ansible Using collections](https://docs.ansible.com/ansible/latest/user_guide/collections_using.html) for more details.

## Contributing to this collection

If you want to develop new content for this collection or improve what is already here, the easiest way to work on the collection is to clone it into one of the configured [`COLLECTIONS_PATH`](https://docs.ansible.com/ansible/latest/reference_appendices/config.html#collections-paths), and work on it there.

For example, if you are working in the `~/dev` directory:

```
cd ~/dev
git clone git@github.com:masterit-dev/ansible-collection-pasteque.git collections/ansible_collections/masterit_dev/pasteque
export COLLECTIONS_PATH=$(pwd)/collections:$COLLECTIONS_PATH
```

You can find more information in the [developer guide for collections](https://docs.ansible.com/ansible/devel/dev_guide/developing_collections.html#contributing-to-collections), and in the [Ansible Community Guide](https://docs.ansible.com/ansible/latest/community/index.html).

### Running tests

See [here](https://docs.ansible.com/ansible/devel/dev_guide/developing_collections.html#testing-collections).

## License

[CC-BY-SA-4.0](https://creativecommons.org/licenses/by-sa/4.0/)

## Author Information

This role was created in 2021 by Lucien DURAND-HARDY from [MasterIT](http//www.masterit.fr)