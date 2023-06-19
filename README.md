# OC-Projet14-Modal

Modal for project 14

# npm install

# In the project into which you are importing the modal, create a State that starts at false

example :
const [show, setShow] = useState(false);

# Then insert the modal component into your jsx.

Example :
<Modal onClose={() => setShow(false)} show={show}>
<p>Employee Created!</p>
</Modal>
