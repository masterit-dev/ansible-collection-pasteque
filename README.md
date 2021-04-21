# Pasteque Collection

This repo contains the `masterit.pasteque` Ansible Collection. The collection includes 2 roles :

* masterit.pasteque_api
* masterit.pasteque_jsadmin

## External requirements

Some roles require external libraries. Please check the requirements for each role you use in the documentation to find out which requirements are needed.

## Included content

Please check the included content on the [Ansible Galaxy page for this collection](https://galaxy.ansible.com/masterit/pasteque)

## Using this collection

Before using the General community collection, you need to install the collection with the `ansible-galaxy` CLI:

    ansible-galaxy collection install masterit.pasteque

You can also include it in a `requirements.yml` file and install it via `ansible-galaxy collection install -r requirements.yml` using the format:

```yaml
collections:
- name: masterit.pasteque
```

See [Ansible Using collections](https://docs.ansible.com/ansible/latest/user_guide/collections_using.html) for more details.



## Contributing to this collection

If you want to develop new content for this collection or improve what is already here, the easiest way to work on the collection is to clone it into one of the configured [`COLLECTIONS_PATH`](https://docs.ansible.com/ansible/latest/reference_appendices/config.html#collections-paths), and work on it there.

For example, if you are working in the `~/dev` directory:

```
cd ~/dev
git clone git@gitlab.com:masterit-public/ansible/ansible-collection-pasteque.git collections/ansible_collections/community/general
export COLLECTIONS_PATH=$(pwd)/collections:$COLLECTIONS_PATH
```

You can find more information in the [developer guide for collections](https://docs.ansible.com/ansible/devel/dev_guide/developing_collections.html#contributing-to-collections), and in the [Ansible Community Guide](https://docs.ansible.com/ansible/latest/community/index.html).

### Running tests

See [here](https://docs.ansible.com/ansible/devel/dev_guide/developing_collections.html#testing-collections).

## Licensing

GNU General Public License v3.0 or later.

See [COPYING](https://www.gnu.org/licenses/gpl-3.0.txt) to see the full text.





