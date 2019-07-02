# FrameLayoutFragment
Display a Custom fragment in Frame Layout


                FragmentManager fragmentManager = getSupportFragmentManager();
                FragmentTransaction fragmentTransaction = fragmentManager.beginTransaction();
                CustomFragment hello = new CustomFragment();
                fragmentTransaction.add(R.id.fragment_container, hello, "HELLO");
                fragmentTransaction.commit();
