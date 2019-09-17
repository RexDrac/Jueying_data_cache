controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
filter-action: True
max-episode-num: 5000000
rollout-step-num: 1
critic-layer-size: [256, 256]
loss-output-bound-coeff: 0.0
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
replay-ratio: 1
render-eval: False
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
critic-activation-fn: ['relu', 'relu', 'None']
state-dim: 25
squash-action: True
tau: 0.001
max-step-num: 2500000000
expert-index: None
loss-output-diff-coeff: 0
interpolation: False
Physics-frequency: 1000
loss-entropy-coeff: 0.0
test-num: 4
imitation-weight: 0.5
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
record-start-size: 10000.0
actor-layer-size: [256, 256]
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
HLC-frequency: 25
dsr-gait-period: 0.6
actor-lr: 0.0003
critic-l2-reg: 0.0003
actor-activation-fn: ['relu', 'relu', 'None']
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-weight-decay: 1e-06
replay-start-size: 10000
joint-interpolation: True
LLC-frequency: 500
env-id: HumanoidBalanceFilter-v0
gating-activation-fn: ['relu', 'relu', 'None']
train-step-num: 1
epoch-num: 500
filter-torque: False
reward-scale: 0.1
max-train-time: 10
batch-size: 128
epoch-step-num: 5000000
action-dim: 12
actor-l2-reg: 0.0003
gating-layer-size: [32, 32]
replay-buffer-size: 1000000
n-step: 1
loss-output-smooth-coeff: 2.0
critic-weight-decay: 1e-06
gamma: 0.955
total-step-num: 2500000000
task-weight: 0.5
bullet-default-PD: False
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-path-num: 20
dsr-gait-freq: 1.667
gating-index: None
prioritized-exp-replay: True
max-path-step: 5000
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
critic-lr: 0.0003
expert-num: 4
max-test-time: 10
