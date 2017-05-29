# Rehan
Messagebox in C#.net code:
DialogResult dr = new DialogResult();
            dr = (MessageBox.Show("Do u want to exit", "info", MessageBoxButtons.YesNo, MessageBoxIcon.Warning));
            if (dr == DialogResult.Yes)
            {
                Application.Exit();
            }
            else if (dr == DialogResult.No)
            {
                MessageBox.Show("ok");
            }
            else
            {

            }
